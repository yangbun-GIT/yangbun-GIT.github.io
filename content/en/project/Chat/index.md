---
title: Chat Program - Development in Linux Environment
date: 2024-06-16 
---

Linux Programming
- Development of a chat program operating in a Linux (Ubuntu) environment

<!--more-->

- Requirements
  - Server: Must accept connections from multiple clients, relay messages, and allow the server administrator to participate in the chat directly
  - Client: Each client connects to the server with its own ID and must be able to exchange messages in real-time with other clients and the server

- Server Implementation
  - Client Management: Add each new client's socket information to a Linked List upon connection for management
  - Concurrency Control: Use a Mutex to prevent thread conflicts when multiple clients connect or disconnect simultaneously, ensuring safe access to the shared client list resource
  - Asynchronous Processing
    - Main Thread: Continuously waits for and accepts new client connection requests
    - Client Processing Thread: Creates one thread per connecting client. Each thread independently waits for messages from its assigned client. Upon receiving a message, it calls the message function to relay it to all other clients
    - Server Input Thread: Creates a separate thread to handle the server administrator's keyboard input. This allows the administrator to input messages and send them to all clients at any time, even while client messages are being processed.

- Client Implementation
  - ID Input and Connection: Upon program startup, it prompts the user for an ID and uses this ID to establish a socket connection to the server.
  - Asynchronous Processing
    - Main Thread: Receives user keyboard input and transmits messages to the server.
    - Message Receiving Thread: Created immediately upon connecting to the server. It waits independently of the main thread for incoming messages and outputs them to the screen upon receipt.

# Multi-Threaded Chat Room
A chat room application built in C++ using the concepts of socket programming and multi-threading.  
It allows multiple clients to connect to a central server and exchange messages in real-time.  
Each client is handled in a separate thread, ensuring smooth concurrency and responsiveness.  


# Features
- Multi-threaded server handling multiple clients simultaneously.  
- Real-time broadcast of messages to all connected users.  
- Thread synchronization using mutexes to avoid race conditions.  
- TCP/IP socket-based communication for reliability.  
- Lightweight and extensible for adding features such as logging, encryption, or performance monitoring.  

## How to run

1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/chat-room.git
   cd chat-room
2. Compile the server and client programs
   ```bash
   g++ server.cpp -lpthread -o server
   g++ client.cpp -lpthread -o client
3. Run the server application
   ```bash
   ./server
4. Open another terminal and run a client application
   ```bash
   ./client
5. To simulate multiple clients, repeat step 4 in additional terminals.

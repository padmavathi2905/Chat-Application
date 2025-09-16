# Chat-Application
This project is a chat room application developed in C++ using socket programming and multi-threading. It demonstrates how real-time communication systems are built at the systems level, focusing on concurrency, synchronization, and networking in a Linux environment.

How to Run

1. Clone this repository

git clone https://github.com/your-username/chat-room.git
cd chat-room


2. Compile the server

g++ server.cpp -lpthread -o server


3. Compile the client

g++ client.cpp -lpthread -o client


4. Run the server

./server


5. Run a client in another terminal

./client


Open multiple clients
Repeat step 5 in additional terminals to simulate multiple participants in the chat room.

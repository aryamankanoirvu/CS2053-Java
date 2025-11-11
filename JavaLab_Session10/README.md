# JavaLab_Session10

## 🎯 Problem Statement
Build a simple TCP client-server application for a two-way chat.

## 🧠 Concepts Practiced
- TCP Socket Programming
- ServerSocket and Socket
- Input/Output streams
- Two-way communication

## 📘 Description
This Java program implements a **two-way chat** between a server and a client using TCP sockets.  
- **Server** listens on port 5000.  
- **Client** connects to the server.  
- Both can send and receive messages until someone types `exit`.

## ⚙️ How to Compile and Run
1. Open **two terminal windows**.
2. Compile both programs:
```bash
javac ChatServer.java
javac ChatClient.java

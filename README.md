# MULTITHREADED-CHAT-APPLICATION

A simple multithreaded chat application in Java using sockets. This project includes both server and client-side code and allows multiple clients to communicate with each other over a local network.

---

## 🚀 Features

- Java-based console chat
- Multithreaded server that handles multiple clients simultaneously
- Each client runs in a separate thread
- Real-time messaging between all connected clients

---

## 🧰 Technologies Used

- Java Sockets
- Multithreading (`Thread` class)
- I/O Streams (`BufferedReader`, `PrintWriter`)
- TCP/IP protocol

---

## 📁 Files

| File Name        | Description                          |
|------------------|--------------------------------------|
| `ChatServer.java`| Main server file, handles connections and broadcasting |
| `ChatClient.java`| Client-side app that connects to the server and sends/receives messages |

---

## 📦 How to Run

### 1. Compile the code

javac ChatServer.java
javac ChatClient.java

### 2. Run the code

java ChatServer

# Chat-Application-
# 💬 Java Chat Application (Client-Server Model)

This is a **real-time chat application** built using Java's **Socket Programming** and **Swing GUI**. It allows a client and a server to communicate over a local network using TCP/IP.


![image alt](https://github.com/anushkagupta1211/Chat-Application-/blob/main/Screenshot%20(254).png?raw=true)

## 🚀 Features

- 🔄 Real-time two-way communication between client and server
- 🎨 GUI for client-side chat using Java Swing
- 🧵 Multi-threading for simultaneous reading and writing
- 📤 Graceful chat termination and connection handling
- 📋 Console-based server interface

---

## 🛠️ Technologies Used

- Java (JDK 8+)
- Java Sockets (`ServerSocket`, `Socket`)
- Java I/O (`BufferedReader`, `PrintWriter`)
- Java Swing (for GUI)

---


## 🖥️ How It Works

1. **Server**:
   - Starts and waits for a connection on port `7777`
   - Accepts a connection from the client
   - Reads messages from the client and writes responses

2. **Client**:
   - Connects to the server on `127.0.0.1:7777`
   - Provides a GUI for user input and displays chat messages
   - Sends and receives messages in real-time

---

## 🧑‍💻 How to Run

### Prerequisites:
- Java installed and set up in your system (`java`, `javac`)

### Steps:

1. **Start the Server**
   
   javac Server.java
   java Server
1. **Start the Client In a new terminal window,**
  run:
   javac Client.java
   java Client

   ***Developed by
Anushka Gupta
B.Tech IT, PSIT Kanpur***


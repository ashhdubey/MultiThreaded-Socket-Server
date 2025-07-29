
# 🚀 MultiThreaded Socket Server in Java

A simple yet powerful Java project demonstrating a multithreaded socket server and multiple clients. This project illustrates how to build a server capable of handling multiple client requests simultaneously using Java threads.

---

## 📁 Project Structure

```
Multithreaded-Java-Socket-Server/
├── README.md
├── Client.java
└── Server.java
```

---

## 🔧 Technologies Used

- ☕ Java SE 8+
- 🧵 Java Threads
- 🌐 Java Networking (Socket & ServerSocket)

---

## 📌 Features

- Handles multiple clients concurrently using threads
- Sends and receives messages via sockets
- Clear and minimal implementation for learning purposes

---

## 🧠 How It Works

### ✅ Server
- Listens on port `8010`
- For every client connection, spawns a new thread to handle the request

### ✅ Client
- Creates 100 client threads
- Each client connects to the server and receives a greeting message

---

## 🚀 How to Run

### 🖥️ Compile

```bash
javac Server.java
javac Client.java
```

### ▶️ Run Server

```bash
java Server
```

### ▶️ Run Client

```bash
java Client
```

---

## 🤝 Contributing

Feel free to fork this repository, make improvements, and create a pull request. All contributions are welcome!

---

## 📄 License

This project is open-source and free to use for educational purposes.

---

## 📬 Contact

Created by **Ashish Dubey** – Feel free to reach out for collaboration or feedback!

---

⭐ If you found this helpful, give it a star on GitHub!



---

````markdown
# 🗨️ Python Chat Application Using Sockets

A real-time chat application built with Python, demonstrating client-server architecture, socket programming, and multithreading. The app supports user registration and login with password hashing, public and private messaging, chat history logging, and an optional GUI client built with Tkinter.

---

## 🚀 Features

- **🔐 User Authentication**  
  Secure login and registration with SHA-256 password hashing.

- **💬 Public & Private Messaging**  
  Chat with all users or send private messages using `/msg <username>`.

- **📝 Chat History Logging**  
  All messages are logged and viewable using the `/history` command.

- **⚙️ Multithreaded Server**  
  Handles multiple clients concurrently for real-time communication.

- **🖼️ Optional GUI Client**  
  Tkinter-based graphical interface for an enhanced chat experience.

---

## 🛠️ Getting Started

### ✅ Prerequisites

- Python 3.x

### 📦 Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/chat-app.git
   cd chat-app
````

2. Run the server:

   ```bash
   python server.py
   ```

3. Run one or more clients in separate terminals:

   ```bash
   python client.py
   ```

4. Or, for the GUI client:

   ```bash
   python client_gui.py
   ```

---

## 💡 Usage

### Client Commands

* **Register/Login:**
  Follow the prompts on client startup.

* **Send Public Message:**
  Simply type your message and hit Enter.

* **Send Private Message:**

  ```
  /msg <username> <message>
  ```

* **View Chat History:**

  ```
  /history
  ```

---

## 📁 Project Structure

```
chat-app/
├── server.py           # Server-side application
├── client.py           # Console client application
├── client_gui.py       # GUI client (Tkinter)
├── users.txt           # Stores user credentials (hashed)
├── chat_history.txt    # Stores chat logs
└── README.md           # This file
```

---

## 🌱 Future Improvements

* 🔐 Add end-to-end encryption
* 📁 Implement file sharing
* 👥 Display online users via `/users` command
* 🎨 Improve GUI with tabs, user list, and themes

---

## 🤝 Contributing

Contributions are welcome!
Feel free to open an issue or submit a pull request to enhance the project.

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 📌 Notes

* This project is intended for educational purposes and personal experimentation.
* Use responsibly if deploying in any real-world environment.

```

---




```

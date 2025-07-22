# P2P-File-Sharing-System

A simple peer-to-peer (P2P) file sharing application built using **Python** and **Tkinter**, implementing a **client-server architecture** for sending and receiving files over a local network.

## 💡 Project Overview

This project is a Computer Networks Lab mini-project that simulates a file-sharing system using socket programming in Python. The graphical interface allows users to either **send** or **receive** files between devices on the same network without relying on a centralized server.

## 📌 Features

- GUI-based interface built with **Tkinter**
- Local file sharing using **socket programming**
- File selection using system file dialog
- Real-time file transmission over TCP
- Sender & Receiver module separation

## 🖥️ How It Works

### Sender Side
1. Click "Send"
2. Select a file
3. Note the system's hostname (ID displayed)
4. Wait for the receiver to connect
5. Click "SEND"

### Receiver Side
1. Click "Receive"
2. Enter the sender's ID (hostname)
3. Provide a filename to save as
4. Click "Receive" to download the file

> ⚠️ Note: Both sender and receiver must be on the **same local network**.

## 🛠️ Technologies Used

- **Python 3**
- **Tkinter** for GUI
- **Socket** module for networking
- **OS** and **filedialog** for file handling

## 📚 Conclusion

This project demonstrates a basic but effective approach to file transfer in a local P2P setup. It leverages Python's built-in libraries to provide a user-friendly and functional application for educational purposes.



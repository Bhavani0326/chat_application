# Chat Application using Python Socket and Tkinter

## About Project

This is a simple chat application made using **Python**, **Socket Programming**, and **Tkinter GUI**.

It has two parts:

* **Server Side**
* **Client Side**

Both users can send and receive messages through a small desktop window.

This project is good for beginners to understand:

* Python networking basics
* Client and server connection
* GUI using Tkinter
* Sending messages using sockets

---

## Features

* Simple chat interface
* Send messages from server to client
* Send messages from client to server
* Message display using Listbox

---

## Technologies Used

* Python
* Tkinter
* Socket Module

---

## Project Files

```bash
chat_application/
│── server.py
│── client.py
│── README.md
```

---

## How It Works

### Server Side

* Creates socket server
* Waits for client connection
* Sends and receives messages

### Client Side

* Connects to server
* Sends messages to server
* Receives messages from server

---

## How to Run

### Step 1: Run Server File

```bash
python server.py
```

### Step 2: Run Client File

```bash
python client.py
```

### Step 3:

* Type message in text box
* Click **Send** button
* Click **Receive** button to get message

---

## Example Output

### Server Window

```text
Server: Hey
Client: Hi 
```

### Client Window

```text
Client: Hi 
Server: Hey
```

---

## What I Learned

* How client-server communication works
* How to use socket in Python
* How to build GUI using Tkinter

---

## Challenges Faced

* Understanding socket connection
* Managing send and receive functions
* Connecting GUI buttons with functions
* Running both files properly


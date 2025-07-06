# Multi-user-chat-application
A foundational real-time chat application demonstrating direct network communication using Python's socket module and concurrent client handling via threading. It features a server that broadcasts messages, supports custom nicknames, and includes basic moderation commands.


## Features
- Real-time messaging between multiple clients  
- Server handles concurrent connections using threads  
- Unique nicknames for each client  
- Broadcasts messages to all connected users  
- Basic admin commands (e.g., `/kick`)

## Technologies Used
- Python 3.x  
- `socket` – for network communication  
- `threading` – for handling concurrency


## Getting Started
### 1. Clone the Repository
Make sure `server.py` and `client.py` are in the same directory.

### 2. Create and Activate a Virtual Environment (Optional)
```bash
python -m venv venv
source venv/bin/activate```  # On Windows: venv\Scripts\activate

### 3. Install Dependencies
No external libraries required – uses only the Python standard library.

### 4. Start the Server
In the first terminal, run:
```bash
python server.py```

### 5. Start the Clients
In another terminal window (or more), run:
```bash
python client.py```

### 6. Enter Your Nickname
When prompted, choose a nickname and join the chat.




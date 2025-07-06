# Multi-user-chat-application
A foundational real-time chat application demonstrating direct network communication using Python's socket module and concurrent client handling via threading. It features a server that broadcasts messages, supports custom nicknames, and includes basic moderation commands.

Features
Real-time messaging between multiple clients
Server handles concurrent connections using threads
Unique nicknames for each client
Broadcasts messages to all connected users
Basic admin commands (e.g., /kick)


Technologies Used
Python 3.x
socket – for network communication
threading – for handling concurrency


Getting Started
Clone the Repository
Make sure server.py and client.py are in the same directory.

Create and Activate a Virtual Environment (Optional but recommended)
'''bash
python -m venv venv
source venv/bin/activate'''        # On Windows: venv\Scripts\activate

Install Dependencies
No external libraries required – uses only the Python standard library.

Start the Server
In the first terminal, run:
'''bash
python server.py'''

Start the Clients
In another terminal window (or more), run:
'''bash
python client.py'''

Enter Your Nickname
When prompted, choose a nickname and join the chat.

# java-console-chat-app

The Java Chat application is a console application that is launched from the command line. 
The server and clients can run on different computers in the same network, e.g. Local Area Network (LAN).

There can be multiple clients connect to a server and they can chat to each other, 
just like in a chat room where everyone can see other users’ messages. 

Every user is notified when a new user arrives and when a user has gone. 
Each message is prefixed with the username to keep track who sent the message.
And finally, the user says ‘bye’ to quit the chat.

Run the Chat Server
-------------------
java ChatServer 8989

Run a Chat Client
-----------------
java ChatClient localhost 8989
        or
java ChatClient <server_ip> 8989

# Chat-programm-between-client-and-server-in-TCP-IP

First we need to compile the server in the Linux terminal.For that we should write this code in the Linux Terminal.
-> gcc server.c -o server
Than we need to compile the client in the Linux Termianl. For that we should write this code in another Linux Terminal.
-> gcc client.c -o client
After compiling our codes in the terminal, we need to run the client and server in their own terminals.
-> ./server
-> ./client (client 1)
Then, every time we open a new tab in the Linux Terminal and run the client, a new user will be connected to our chat program. (client 1, client 2, ....)
-> ./client (client 2)
-> ./client (client 3)
.
.
.

Portfolio Project Blog post

two sockets process which is sending and receiving bytes.  Steps involved in this process is as follows:

Task 0
1. Create socket
2. Communicate the socket address
3. Keep waiting for an incoming connection request/s
4. Connect to client
5. Receive the message
6. Decode the destination user and select the socket
7. Send a message to the intended client
8. Keep repeating step 5 & 6 as per users wish
9. Exit i.e. end the communication by terminating the connection

Task. 1
only connect with the server and send and receive messages. The steps involved in client script are:

1. Create a unique client socket per instance/user
2. Connect to the server with given socket address (IP and port)
3. Send and receive messages
4. Repeat step 3 as per configuration
5. Close the connection

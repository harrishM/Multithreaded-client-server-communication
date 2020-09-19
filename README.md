# Multithreaded-client-server-communication
Implemented multi-threaded communication.


Step 1) Open the Client and Server folders in Netbeans.

Step 2) Right click on server and click RUN.
Step 3) The Server GUI will start up.
Step 4) Click on Start and the server would start up.
Step 5) Start the Client process as such and repeat it 3 times.
Step 6) This is how all the opened server and 3 clients would look like.
Step 7) Enter usernames for each of the client and here is a demonstration of a client entering
a username that has already been registered.
Step 8) All the users are now registered and when u click the “Online users” button on the
server, it would display all the connected users on the server GUI.
Step 9) Click the “Random” button on the server and it will randomly pick a number between
3-9 and it will send It to a connected client at random and the server would repeat the process
every 10 seconds.
Step 10) When Skip button is pressed, the client will skip the count down. The server will
continue waiting for its 10 seconds before sending the next request to the random client.
Step 11) Once all the clients have disconnected, the server will end all connections and display
the requests sent. And finally, I have clicked “Online Users” button again to show that all the
clients have disconnected.
Additional Info:
1) Client disconnection in-between count down has been handled.
2) Server will not end its session before every client has disconnected.

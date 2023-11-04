GUI Setup:

The program creates a graphical user interface (GUI) using Java Swing components. The GUI includes a window (JFrame) with various elements such as text fields, labels, buttons, and message display areas.
The user interface is designed to resemble a chat application, with message input at the bottom and a message display area above.
Client and Server Setup:

The code can run as both a client and a server. The client and server roles are defined within the same program.
It listens on a socket (port 6001) for incoming connections when running as a server.
Message Input:

Users can enter text messages in the text field at the bottom of the application window.
Message Sending:

When a user clicks the "Send" button, the actionPerformed method is triggered. It retrieves the message from the text field, creates a message panel (formatLabel), and sends the message to the other user (client or server) using a DataOutputStream.
Message Display:

Messages are displayed in a chat area in the middle of the application window. Each message is displayed in a panel, and the panels are arranged in a vertical box layout to create a chat history.
Chat History Layout:

Messages from the user are displayed on the right side of the chat area (client) or the left side (server). The formatLabel method formats and styles the message panels, adding a background color, border, and timestamp.
Server and Client Interaction:

The server listens for incoming connections using a ServerSocket.
When a connection is established, the server and client can send and receive messages from each other.
Closing the Application:

Users can close the application window by clicking the arrow icon at the top.
Here's how the code works in a typical scenario:

You can run the program as a server or client.
When running as a server, it listens for incoming connections on port 6001.
When running as a client, it connects to the server at the IP address "127.0.0.1" (localhost) and port 6001.
Users can type messages in the text input field and click the "Send" button to send messages.
The messages are formatted, displayed in the chat area, and sent to the other user.
The chat history is maintained and displayed in a vertical layout.

![Screenshot 2023-11-04 175919](https://github.com/amanraut29/Chat_space/assets/123371627/a58d1ac2-c04d-4d89-9f94-02105af0ad8d)





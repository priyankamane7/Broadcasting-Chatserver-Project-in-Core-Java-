# Broadcasting-Chatserver-Project-in-Core-Java-

Broadcasting Chatserver
This project implements a simple broadcasting chat server. Clients can connect to the server to send and receive messages in real-time, enabling group chat functionality.

Project Structure
The project files are organized as follows:

client.mf: Manifest file containing metadata for the client.

MyClient.jar: Packaged JAR file for the client application, containing all necessary compiled classes.

MyServer.java: Java source file for the server, responsible for handling multiple client connections and broadcasting messages to all connected clients.

Client and Server Class Files:

MyClient.class, MyClient$1.class, MyClient$2.class: Compiled client classes with inner classes to handle GUI or user interactions.
MyServer.class: Compiled server class for managing client connections and message broadcasting.
ClientThread.class: Manages individual client threads on the server side.
MyThread.class: Additional threading support, likely used for client-server communication.
temp.txt: Temporary file, may contain sample configurations or logs.

Prerequisites
Java Development Kit (JDK) version 8 or higher.
A terminal or command prompt.

How to Run
Start the Server:
Compile the server file if needed:

javac MyServer.java
Run the server:
java MyServer
The server will start listening for client connections on a specified port.

Start the Client:
Run the MyClient.jar file:
java -jar MyClient.jar

Multiple clients can be launched to join the chat.
Features
Broadcasting: The server broadcasts each client's message to all connected clients.
Multithreading: Each client connection is handled in a separate thread, ensuring smooth real-time communication.

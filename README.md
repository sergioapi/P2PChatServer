# P2P Messaging System Server using Java RMI

This project is part of the Distributed Computing course and involves developing the server-side application of a P2P messaging system using Java RMI. The server application is responsible for managing user registrations, handling client connections, and maintaining the overall communication infrastructure of the system.

## Features

- **Client Connections**: Accepts connections from multiple clients, notifies other clients of new connections, and informs the newly connected client of online users.
- **User Notifications**: Informs all clients when a user connects or disconnects.
- **Direct Messaging**: Clients send and receive messages directly without routing through the server.
- **Friend Groups**: Manages groups of friends, allowing users to send and receive friend requests and notifications only within their friend group.
- **Persistent Storage**: Uses a database to store user information, friend groups, and pending friend requests.

## Functionality

- **Notify Clients of New Connections**: When a new client connects, the server notifies all connected clients and provides the new client with a list of currently online users.
- **Notify Clients of Disconnections**: When a client disconnects, the server notifies all connected clients of the disconnection.
- **Friend Requests**: Allows users to send friend requests, even if the recipient is offline. Pending requests are stored on the server and processed when the recipient comes online.
- **Group Management**: Users can manage their friend groups, and notifications are sent only to users within the same group.

## Credits
This project was developed as part of the Distributed Computing course by Sócrates Agudo Torrado and Sergio Álvarez Piñón

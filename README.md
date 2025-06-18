COMPANY:CODETECT IT SOLUTIONS

NAME:ARFA PARVEEN

INTERN ID:CT04DN696

DOMAIN:FULL STACK

DURATION:4 WEEKS

Task Description: Real-Time Collaborative Document Editor
In this task, we built a Real-Time Collaborative Document Editor using React.js, Node.js, Express, and Socket.io. The purpose of this project is to allow multiple users to edit a text document simultaneously from different browsers or devices, with their changes instantly reflected to all connected users in real time. This type of application is commonly used in online document tools like Google Docs and collaborative note-taking apps.

The project is divided into two main parts: the frontend and the backend. The frontend is built with React.js and provides a simple user interface containing a text area where users can type or edit content. The backend is built using Node.js and Express, and it uses Socket.io to handle real-time, bidirectional communication between the frontend clients. Whenever one user makes a change to the document, that change is instantly broadcasted to all other connected users.

To set up the project, we first created a React application using create-react-app. Inside the React app, we created a component called App.js, which contains a text area and manages the state of the document using React hooks like useState and useEffect. The text area is connected to a Socket.io client, which listens for incoming updates from the server and emits updates whenever the content is changed by the user. This ensures that all connected clients remain synchronized with the latest document content.

On the backend side, we set up an Express server and integrated Socket.io to handle real-time connections. When a client connects, the server logs their connection ID. Whenever a client emits an "edit" event with updated document content, the server broadcasts this new content to all other connected clients, ensuring that everyone sees the same document content instantly. The server listens for both connection and disconnection events, managing the real-time interactions efficiently.

To run the project, we use two terminal windows or tabs. In one terminal, we run the backend server using node server.js, which starts the server on port 4000. In the other terminal, we navigate to the React app folder and run npm start, which starts the frontend on port 3000. The frontend then connects to the backend via Socket.io and allows users to interact with the collaborative editor.

When testing the application, we can open http://localhost:3000 in two or more browser windows or tabs. As soon as a user types into the text area in one window, the same content appears in real time in the other windows, demonstrating the collaborative functionality. This task helps in understanding how real-time web applications work, how web sockets enable instant data transfer, and how to integrate React with a Node.js backend using Socket.io.

Overall, this project provides a simple and practical example of implementing real-time communication in web development. It covers essential concepts such as managing client-server communication, using state in React, handling events with Socket.io, and building a full-stack application using modern web technologies.

OUTPUT:

![Image](https://github.com/user-attachments/assets/fdcc4697-2039-422e-8eb3-2355bc749bb1)

![Image](https://github.com/user-attachments/assets/2a109f88-02e7-4cf2-95bb-9be68af486bf)

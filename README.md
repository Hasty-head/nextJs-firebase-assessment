# Virtual Event Space - Take-Home Task

## Objective
Build a virtual event space where users can create an event, join different event rooms, and interact through messages in real-time.

## Core Features

### Event Creation and Management
- Users can create an event with a title, description, date, and time.
- The creator can add multiple rooms to the event (e.g., for talks, networking, etc.).
- Use Firebase Firestore to store event and room data.

### Real-time Messaging in Rooms
- Implement real-time messaging within each room using Firebase Realtime Database or Firestore.
- Users should be able to join any room and see messages being broadcast in real-time.

### User Authentication and Profiles
- Implement user authentication using Firebase Authentication.
- Users can create and edit a simple profile with a username and avatar.

### Frontend with Next.js
- Use Next.js for server-side rendering of the event pages.
- Implement dynamic routing to handle different event and room URLs.

### State Management
- Manage the state of messages, rooms, and user interactions efficiently.
- Ensure that the user experience is smooth and that the UI updates reflect the real-time nature of the app.

### Access Control
- Creators can set events as public or private.
- For private events, implement a simple invitation system using Firebase functions.

## Additional Requirements
- The application must be written in TypeScript.
- Design a simple and intuitive user interface.
- Write clean, modular, and reusable code.
- Ensure the application is responsive and works well on both desktop and mobile browsers.
- Provide thorough documentation in a `README.md` file, including how to run the application, a brief explanation of the architecture, and any design decisions made during development.
- The project needs to be deployed and accessible online. Include deployment instructions and the link to the deployed application in the documentation.

## Evaluation Criteria
- Effective use of Firebase services for real-time interactions and data storage.
- Well-structured Next.js application with proper server-side rendering and dynamic routing.
- Robust user authentication and profile management.
- Good state management practices, especially in the context of real-time updates.
- Code quality, including readability, maintainability, and adherence to best practices.
- Thoughtful UI/UX design and attention to detail.
- Quality and clarity of documentation.

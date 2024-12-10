### **Project Name: StreamChat**

---

### **Overview:**
**StreamChat** is a real-time chat application built using the MERN stack. It provides seamless real-time messaging, user authentication, profile updates, and a responsive design. Features include online/offline status, cloud-based media storage, and chat persistence, making it a robust platform for communication.

---

### **Mission and Objectives**

#### **Mission:**
To develop a scalable, user-friendly, and interactive real-time chat application with advanced features for seamless communication.

#### **Objectives:**
1. Implement secure user authentication and profile management.
2. Provide real-time messaging using **Socket.IO**.
3. Enable profile customization with support for profile picture updates.
4. Design a fully responsive UI for various devices.
5. Use cloud storage for managing user media and persistent chat data.
6. Deploy the application for global accessibility.

---

### **Technology Stack**

#### **Frontend**
1. **React.js**
   - **Why:** Facilitates dynamic UI rendering and interactive interfaces.
   - **Use Case:** Builds the chat interface, user profile pages, and message feed.

2. **Tailwind CSS**
   - **Why:** Simplifies styling with utility-first classes.
   - **Use Case:** Creates a responsive, modern design for both desktop and mobile.

#### **Backend**
1. **Node.js**
   - **Why:** Enables scalable server-side execution.
   - **Use Case:** Handles API requests, real-time connections, and user management.

2. **Express.js**
   - **Why:** Simplifies routing and middleware handling.
   - **Use Case:** Manages APIs for user authentication and messaging.

3. **Socket.IO**
   - **Why:** Powers real-time, bi-directional communication.
   - **Use Case:** Handles real-time messaging and online/offline status.

#### **Database**
1. **MongoDB**
   - **Why:** A NoSQL database ideal for dynamic and scalable data storage.
   - **Use Case:** Stores user data, messages, and session details.

2. **Mongoose**
   - **Why:** Simplifies MongoDB interactions with schema-based models.
   - **Use Case:** Manages structured data relationships for the app.

#### **Authentication**
1. **JWT (JSON Web Tokens)**
   - **Why:** Provides secure token-based authentication.
   - **Use Case:** Authenticates and authorizes user access.

2. **Bcrypt.js**
   - **Why:** Hashes sensitive information like passwords.
   - **Use Case:** Secures user credentials.

#### **Deployment**
1. **Heroku/AWS**
   - **Why:** For scalable application hosting.
   - **Use Case:** Deploys the app and database.

2. **Cloudinary**
   - **Why:** Offers cloud-based storage for media files.
   - **Use Case:** Stores profile pictures and other user-uploaded files.

---

# Project Structure for Feature Implementation
This project is structured to ensure a systematic and incremental development process. Each week builds upon the previous deliverables, enabling a smooth transition from basic functionalities to advanced features.

---

**NOTE:**
Participants are encouraged to customize the user interface and incorporate additional features into the application. These modifications allow participants to demonstrate creativity, improve usability, and enhance the functionality of the project. Such enhancements align with the project’s objective of fostering innovative thinking while providing a personalized learning experience.

---

### **Week-by-Week Plan**

---

#### **Week 1: Project Setup**
- **Goal:** Set up the foundational structure for ChatVerse.

- **Tasks:**
  1. Install and configure Node.js, MongoDB, and React.
       - **Reading:** [Setting Up MERN Stack](https://www.mongodb.com/mern-stack)  
       - **Video:** [MERN Stack Crash Course](https://www.youtube.com/watch?v=fnpmR6Q5lEc)
  2. Create the project directory structure.
     - **Reading:** [React App Structure](https://reactjs.org/docs/getting-started.html)
  3. Build a basic Express server and connect it to MongoDB.
     - **Reading:** [Express.js Basics](https://expressjs.com/)
     - **Video:** [Express Server Setup](https://www.youtube.com/watch?v=L72fhGm1tfE)
  4. Install Tailwind CSS for styling.
    - **Reading:** [Tailwind CSS Docs](https://tailwindcss.com/docs/installation)
     - **Video** [Tailwind CSS lecture](https://www.youtube.com/watch?v=UBOj6rqRUME)

- **Deliverables:**
  - Basic project setup with backend and frontend initialized.

---

#### **Week 2: User Authentication**
- **Goal:** Implement user registration, login, and secure authentication.

- **Tasks:**
  1. Create user schemas using Mongoose.
     - **Reading:** [MongoDB Schema Design](https://mongoosejs.com/docs/guide.html)  
     - **Video:** [Mongoose Models Tutorial](https://www.youtube.com/watch?v=DZBGEVgL2eE&t=30s)
  2. Set up user authentication APIs with JWT.
     - **Reading:** [JWT Basics](https://jwt.io/introduction/)
     - **Video:** [JWT Implementation](https://www.youtube.com/watch?v=mbsmsi7l3r4&t=1364s)
  3. Build login and signup forms in React.
     - **Reading:** [React Forms](https://react.dev/reference/react-dom/components/form)
     - **Video:** [Building Forms in React](https://www.youtube.com/watch?v=SdzMBWT2CDQ&t=1s)

- **Deliverables:**
  - Functional user registration and login system.

---

#### **Week 3: Real-Time Messaging**
- **Goal:** Enable real-time messaging using **Socket.IO**.

- **Tasks:**
  1. Set up **Socket.IO** on the backend and frontend.
     - **Reading:** [Socket.IO Basics](https://socket.io/docs/v4/tutorial/step-3)
     - **Video:** [Real-Time Messaging with Socket.IO](https://www.youtube.com/watch?v=UUddpbgPEJM&t=563s)
  2. Implement message delivery and status updates.
     - **Reading:** [Real-Time Updates](https://socket.io/get-started/chat)
     - **Video:** [Building Chat Apps](https://www.youtube.com/watch?v=CzcfeL7ymbU)

- **Deliverables:**
  - Fully functional real-time chat system.

---

#### **Week 4: Profile Management**
- **Goal:** Allow users to update their profiles, including uploading profile pictures.

- **Tasks:**
  1. Integrate **Cloudinary** for profile picture storage.
     - **Reading:** [Cloudinary Setup](https://cloudinary.com/documentation)
     - **Video:** [Image Upload with React and Cloudinary](https://www.youtube.com/watch?v=GML8Mw449O4)
  2. Implement profile update APIs.
     - **Reading:** [Node.js CRUD APIs](https://nodejs.org/api/n-api.html)
     - **Video:** [Profile Update Tutorial](https://www.youtube.com/watch?v=cB_wOu9rGF8)

- **Deliverables:**
  - Profile management with picture upload functionality.

---

#### **Week 5: UI Enhancements and Error Handling**
- **Goal:** Make the UI responsive and improve error handling.

- **Tasks:**
  1. Style the application using **Tailwind CSS** and **DaisyUI**.
    - **Reading:** [Tailwind CSS Docs](https://tailwindcss.com/docs/installation)
    - **Video** [Tailwind CSS lecture](https://www.youtube.com/watch?v=UBOj6rqRUME)
    -  **Reading** [Daisy CSS Docs](https://daisyui.com/)
    -  **Video** [Daisy Tutorial](https://www.youtube.com/watch?v=UfkrWf5jwrA)
  2. Add error and loading state handling.
     - **Reading:** [Error Boundaries in React](https://www.freecodecamp.org/news/effective-error-handling-in-react-applications/)
     - **Video:** [Error Handling in React](https://www.youtube.com/watch?v=_xe20niOoGY)

- **Deliverables:**
  - Responsive design and robust error handling.

---

#### **Week 6: Deployment**
- **Goal:** Deploy the application and ensure it’s production-ready.

- **Tasks:**
  1. Deploy the app using Heroku or AWS.
     - **Reading:** [Deploying MERN Apps](https://dev.to/kunalukey/how-to-setup-and-deploy-a-mern-stack-project-for-free-5acl)
     - **Video:** [Deploying React and Node.js Apps](https://www.youtube.com/watch?v=l134cBAJCuc)
  2. Test all features and finalize the project.

- **Deliverables:**
  - Live ChatVerse app accessible online.

---

**Checkout the screenshots for your reference**

![Screenshot (144)](https://github.com/user-attachments/assets/04303869-e571-40da-9d70-b1ac67c3cad0)
![Screenshot (145)](https://github.com/user-attachments/assets/59e30674-1506-4ec5-a942-51e3d745bb51)
![Screenshot (146)](https://github.com/user-attachments/assets/d79e740d-5e17-419c-a81e-7f04b3f4c0cc)
![Screenshot (149)](https://github.com/user-attachments/assets/10c50aef-a438-4c3f-8903-e62c94bbb9d0)
![Screenshot (150)](https://github.com/user-attachments/assets/022ae649-484c-4364-af8a-28592ea1dae2)
![Screenshot (151)](https://github.com/user-attachments/assets/acdee84c-9654-4240-b6e5-a734162d95b1)
![Screenshot (152)](https://github.com/user-attachments/assets/b00dfb7e-0341-4576-af14-fe9761f4b204)
![Screenshot (142)](https://github.com/user-attachments/assets/473260c4-3f05-454c-beab-4b6d42b16b8b)


## References:
- https://github.com/burakorkmez/fullstack-chat-app
- https://www.youtube.com/watch?v=ntKkVrQqBYY

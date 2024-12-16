
### **Project Overview: TrackIt Expense Tracker Web App**

**TrackIt:** This project involves building a comprehensive expense tracker web application using the MERN stack (MongoDB, Express.js, React.js, and Node.js). It is designed to track both income and expenses with support for user authentication, admin privileges, data visualization, and pagination. Participants will learn modern web development techniques and Redux Toolkit for state management.

---

### **Mission and Objectives**

**Goal:**  
By the end of this project, participants will develop a fully functional expense tracker web application with features like secure authentication, role-based access, detailed reports, and a responsive user interface.

**Objectives:**  
1. Develop a MERN-based web application for tracking income and expenses.
2. Implement user authentication with role-based access (admin and user roles).
3. Provide data visualization with charts for expense and income insights.
4. Create a responsive UI using modern CSS frameworks.
5. Deploy the application for real-world access.

---

### **Technology Stack**

#### **Frontend**
1. **React.js**  
   - **Why?**: Enables building modular and dynamic UI components.  
   - **Use Cases**: Creating components for user profiles, transactions, and reports.

2. **Redux Toolkit**  
   - **Why?**: Simplifies state management with efficient tools for managing global state.  
   - **Use Cases**: Managing transaction data, user sessions, and pagination.

3. **Chart.js**  
   - **Why?**: Provides dynamic and interactive charts for data visualization.  
   - **Use Cases**: Creating pie charts and bar graphs for income and expense summaries.

4. **CSS Frameworks** (Tailwind CSS or Bootstrap)  
   - **Why?**: Enables rapid and responsive UI design.  
   - **Use Cases**: Styling forms, tables, and navigation components.

---

#### **Backend**
1. **Node.js**  
   - **Why?**: Provides a scalable runtime environment for backend logic.  
   - **Use Cases**: Handling server-side logic and API endpoints.

2. **Express.js**  
   - **Why?**: Simplifies backend development with routing and middleware.  
   - **Use Cases**: Building RESTful APIs for authentication, transactions, and reports.

3. **MongoDB**  
   - **Why?**: Offers a flexible schema for hierarchical data like users, roles, and transactions.  
   - **Use Cases**: Storing user profiles, income, and expense records.

4. **Mongoose**  
   - **Why?**: Simplifies interaction with MongoDB through schema-based models.  
   - **Use Cases**: Defining schemas for users, transactions, and roles.

---

#### **Deployment**
1. **Frontend Hosting**: Vercel or Netlify  
   - **Why?**: Optimized for React applications with CI/CD and global CDN.  
   - **Use Cases**: Hosting the frontend application.

2. **Backend Hosting**: Heroku or Render  
   - **Why?**: Provides scalable hosting for Node.js backend.  
   - **Use Cases**: Hosting the Express API and MongoDB database.

---

### **Workflow Overview**
This section illustrates the interaction between the React frontend, Express backend, MongoDB database, and Redux Toolkit for state management.

---

### **System Architecture**
The architecture of **TrackIt** emphasizes modular design with separate layers for the frontend, backend, and database. It uses RESTful APIs for secure communication and state management with Redux Toolkit.
![image](https://github.com/user-attachments/assets/4a3978b8-5f92-4e3f-ba66-d57e1d89e1f5)


---

### **Project Structure for Feature Implementation**
This project is structured to ensure a systematic and incremental development process. Each week builds upon the previous deliverables, enabling a smooth transition from basic to advanced functionalities.

**NOTE:** Participants are encouraged to customize the design and functionality to make the application unique.

---

### **Week-by-Week Learning Plan**

#### **Week 1: Environment Setup and Basic Server**
- **Tasks**:
  1. Set up the project structure with separate client and server folders.
     - **Reading**: [MERN Stack Folder Structure](https://www.mongodb.com/mern-stack)  
     - **Video**: [Folder Structure for MERN Projects](https://www.youtube.com/watch?v=98BzS5Oz5E4&list=PL4cUxeGkcC9iJ_KkrkBZWZRHVwnzLIoUE)
  2. Create a basic Express.js server with a health check endpoint.
     - **Reading**: [Getting Started with Express.js](https://expressjs.com/en/starter/installing.html)  
     - **Video**: [Setting Up an Express Server](https://www.youtube.com/watch?v=L72fhGm1tfE)

- **Deliverables**:
  - A functional backend server with a running endpoint.

---

#### **Week 2: Authentication System**
- **Tasks**:
  1. Implement JWT-based user authentication.
     - **Reading**: [JSON Web Tokens](https://jwt.io/introduction/)  
     - **Video**: [JWT Authentication in Node.js](https://www.youtube.com/watch?v=mbsmsi7l3r4)
  2. Add role-based access control for admin and user roles.
     - **Reading**: [Role-Based Authentication](https://dotnetfullstackdev.medium.com/role-based-authorization-and-authentication-in-react-with-auth-handlers-specific-role-based-and-466c4483a2fb)  
     - **Video**: [Role-Based Access in Express](https://www.youtube.com/watch?v=HHuiV841g_w)

- **Deliverables**:
  - Secure authentication system with role-based access control.

---

#### **Week 3: Income and Expense Tracking**
- **Tasks**:
  1. Create APIs for managing income and expenses.
     - **Reading**: [Building RESTful APIs](https://restfulapi.net/)  
     - **Video**: [Creating APIs with Express](https://www.youtube.com/watch?v=pKd0Rpw7O48)
  2. Implement frontend forms for adding and editing transactions.
     - **Reading**: [React Forms](https://reactjs.org/docs/forms.html)  
     - **Video**: [Building Forms in React](https://www.youtube.com/watch?v=YK1Sw_hnm58)

- **Deliverables**:
  - A functional backend and frontend for managing transactions.

---

#### **Week 4: Reports and Data Visualization**
- **Tasks**:
  1. Add charts for income and expense summaries.
     - **Reading**: [Chart.js Documentation](https://www.chartjs.org/docs/latest/)  
     - **Video**: [Using Chart.js in React](https://www.youtube.com/watch?v=Ly-9VTXJlnA)
  2. Provide detailed reports with filtering options.
     - **Reading**: [React Data Tables](https://react-table.tanstack.com/)  
     - **Video**: [Building Data Tables](https://www.youtube.com/watch?v=jAQpO_MUwpI)

- **Deliverables**:
  - Interactive charts and detailed reports for transactions.

---

#### **Week 5: Pagination and Deployment**
- **Tasks**:
  1. Implement pagination for transaction lists.
     - **Reading**: [Pagination in MongoDB](https://docs.mongodb.com/manual/reference/method/cursor.skip/)  
     - **Video**: [Pagination with Node.js and MongoDB](https://www.youtube.com/watch?v=ZYKOoEXaCIM)
  2. Deploy the application.
     - **Reading**: [Deploying MERN Apps](https://www.mongodb.com/developer/how-to/deploy-mern-app/)  
     - **Video**: [Deploy MERN Stack](https://www.youtube.com/watch?v=9FAHZX5Cmu4)

- **Deliverables**:
  - A deployed application with live access.

---

#### **Screenshots for Reference**

![Screenshot (235)](https://github.com/user-attachments/assets/1bf8d8a3-e93a-4e12-839e-e636a56b4fdd)
![Screenshot (236)](https://github.com/user-attachments/assets/1c318cb5-18aa-431d-9f5a-61c98c4988f1)
![Screenshot (237)](https://github.com/user-attachments/assets/0f8e4924-747c-41b8-ab8c-8d065a23295c)
![Screenshot (238)](https://github.com/user-attachments/assets/28b4bb6e-ac5c-43a6-9f1b-f886c0f17723)
![Screenshot (239)](https://github.com/user-attachments/assets/480be0e5-8c92-4ef8-80b3-c990e3b64afe)
![Screenshot (240)](https://github.com/user-attachments/assets/f8394d6f-5524-4250-8a05-78542a2e558b)
![Screenshot (241)](https://github.com/user-attachments/assets/30218b6c-44d8-4200-b82b-e1f196a27730)
![Screenshot (242)](https://github.com/user-attachments/assets/235dcc4a-19ea-4472-964f-863e2f35f11b)
![Screenshot (243)](https://github.com/user-attachments/assets/29584251-4987-43cd-b3db-39c9fe3555bc)
![Screenshot (233)](https://github.com/user-attachments/assets/eb574792-9fde-4e60-a3a5-c3b524716565)

---

## **References:**
1. [React Documentation](https://reactjs.org/docs/getting-started.html)
2. [Express.js Documentation](https://expressjs.com/)
3. [MongoDB Docs](https://docs.mongodb.com/)
4. [Chart.js Documentation](https://www.chartjs.org/docs/latest/)
5. [Redux Toolkit Documentation](https://redux-toolkit.js.org/)
6. https://github.com/tweneboah/expense-tracker-frontend-v1
7. https://www.youtube.com/playlist?list=PLakAmVjYWIY6RoTI8Xm1dCuNTn2zmz44x

---


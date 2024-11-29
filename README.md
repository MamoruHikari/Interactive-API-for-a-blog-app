# Interactive API for a Blog App

This project features a custom-built interactive API for a blog app using Node.js and Express to serve dynamic content.

---

## **Project Structure**

- **`AppServer.js`**: The main application server running on port `3000`. It serves the frontend content and interacts with the API.
- **`API.js`**: The API server running on port `4000`. It handles blog-related data, including retrieving, adding, and updating blog posts.
- **`public/styles/`**: Contains CSS styles for the frontend UI.
- **`views/`**: Houses HTML or EJS templates used for rendering the blog app interface.

---

## **Getting Started**

### **Prerequisites**
- Install [Node.js](https://nodejs.org/) and npm on your machine.

### **Installation**
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Interactive-API-for-a-blog-app.git
   cd Interactive-API-for-a-blog-app
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

### **Running the Servers**
- Start the API server (port 4000):
  ```bash
  node API.js
  ```

- Start the application server (port 3000):
  ```bash
  node AppServer.js
  ```

### **Accessing the App**
Open your browser and navigate to:
   - **Application Server**: [http://localhost:3000](http://localhost:3000)
   - **API Server**: [http://localhost:4000](http://localhost:4000)

---

## **Project Goals**
- Learn how to build and manage APIs using Node.js and Express.
- Create a functional API for a blog app, supporting actions like fetching, adding, and updating posts.
- Understand how to structure the interaction between an API server and an application server in a full-stack app.

---

## **Key Features**
- **API**: Handles blog data operations such as:
  - Fetching blog posts
  - Adding new blog posts
  - Updating and deleting posts
- **Frontend**: The app displays the blog content and interacts with the API to perform actions.

---

Feel free to test the project locally and explore the interaction between the frontend and API.

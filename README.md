# 3-Tier DevSecOps User Management Demo 📝

This repository contains a simple Node.js Server and a React client to demonstrate a basic user management application. This project serves as a practical example of a 3-tier architecture within a DevSecOps pipeline.

## Getting Started

Follow the steps below to get the project running on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have the following installed on your system:

* **Node.js**: Version 18.x or later is recommended. You can download it from [nodejs.org](https://nodejs.org/).
* **npm**: (Node Package Manager) This is included with your Node.js installation.

### Installation

1.  **Clone the repository:**
    If you haven't already, clone the project to your local machine.
    ```bash
    git clone [https://github.com/ivtanel152/3-Tier-DevSecOps-Project.git](https://github.com/ivtanel152/3-Tier-DevSecOps-Project.git)
    cd 3-Tier-DevSecOps-Project
    ```

2.  **Install Backend Dependencies:**
    Navigate to the Server directory and install the required packages.
    ```bash
    cd server
    npm install
    ```

3.  **Install Frontend Dependencies:**
    From the root project folder, navigate to the client directory and install its packages.
    ```bash
    cd ../client
    npm install
    ```

## Running the Application 🏃‍♂️

You will need **two separate terminal windows** to run both the backend Server and the frontend Client simultaneously.

---

### **Terminal 1: Start the Backend Server**

1.  Navigate to the `Server` directory from the project root.
    ```bash
    cd server
    ```
2.  Run the start command.
    ```bash
    npm start
    ```
    > The Server will now be running on [http://localhost:8080](http://localhost:8080).

---

### **Terminal 2: Start the Frontend Client**

1.  In a new terminal, navigate to the `Client` directory from the project root.
    ```bash
    cd client
    ```
2.  Run the start command.
    ```bash
    npm start
    ```
    > This will launch the development server for the React application.

---

### View in Browser

Once the client development server has started, open your web browser and navigate to:

**[http://localhost:3000](http://localhost:3000)**

You should now see the user management application running!

3-Tier DevSecOps Project: User Management DemoThis repository contains a simple Node.js API and a React client designed to demonstrate a basic user management application. This project serves as a practical example of a 3-tier architecture within a DevSecOps pipeline.🚀 Getting StartedFollow the steps below to get the project running on your local machine for development and testing purposes.PrerequisitesBefore you begin, ensure you have the following installed on your system:Node.js: Version 18.x or later is recommended. You can download it from nodejs.org.🛠️ Setup and InstallationClone the repository (if you haven't already):git clone <your-repository-url>
cd <your-repository-directory>
Install API Dependencies: Navigate to the api directory and install the required npm packages.cd api
npm install
Install Client Dependencies: Navigate to the client directory from the root folder and install its npm packages.cd ../client
npm install
▶️ Running the ApplicationYou will need two separate terminal windows to run both the backend API and the frontend client simultaneously.Start the API Server:In your first terminal, navigate to the api directory and run the start command.cd api
npm start
The API will typically start on http://localhost:8080 or another specified port.Start the React Client:In your second terminal, navigate to the client directory and run the start command.cd client
npm start
This will launch the development server for the React application.View in Browser:Once the client has started, open your web browser and navigate to:http://localhost:3000You should now see the user management application running!
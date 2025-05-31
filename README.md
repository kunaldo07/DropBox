Installation and Setup
Prerequisites:

Node.js (v14.x or higher)
MongoDB (locally or using Docker)
npm (Node Package Manager)

Steps to Run the Project:

1. Clone the Repository:

git clone https://github.com/kunaldo07/DropBox.git
cd dropbox

2. Install Backend Dependencies:

Navigate to the backend directory and install the required dependencies:
cd backend
npm install

3. Set Up MongoDB:

Create MongoDB cluster and put its CONNECTION_STRING in .env file.
Add PORT = 5001 in .env.

4. Start the Backend Server:

In the backend directory, run the following command:
npm start
This will start the backend server on http://localhost:5001.

5. Install Frontend Dependencies:

Navigate to the frontend_ directory and install the required dependencies:
cd ../frontend_
npm install

6. Start the Frontend Development Server:

In the frontend_ directory, run the following command:
npm run dev
This will start the frontend development server on http://localhost:3000.

7. Open the Application:

Open your browser and go to http://localhost:3000 to access the application.
You can now upload, download, and view files.
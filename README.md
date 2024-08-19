# Running Machine Learning-based Spam Email Identification and Elimination Project in Visual Studio Code

## Prerequisites
- Node.js
- Python
- Required Python Libraries:
  - pandas
  - scikit-learn
  - matplotlib
  - seaborn
  - numpy

## Steps

1. **Open Visual Studio Code:**
   - Launch Visual Studio Code.

2. **Open Project Folder in Visual Studio Code:**
   - Open the main project folder in Visual Studio Code.

3. **Open Integrated Terminal:**
   - Navigate to the menu bar and click on `Terminal` > `New Terminal`> 'Split Terminal' to open the integrated terminals within Visual Studio Code.

4. **Install Required Python Libraries:**
   - In the terminal, install the required Python libraries:
     ```
     pip install pandas scikit-learn matplotlib seaborn numpy
     ```

ONCE EVERYTHING IS INSTALLED
1. **Navigate to Project Folders:**
   - In the integrated terminals, navigate to the frontend folder of your project: type "cd frontend"
    
   - Next, navigate to the backend folder of your project: type "cd backend"
    
2. **Start Backend (Flask):**
   - In the terminal (backend folder), start the Flask server:

     type: python flask_server.py
     This completes whats needed for the backend
    
3. **Start Frontend (React):**
   - In the terminal (frontend folder), start the React application:
     type: cd email_spammer
     
     type: npm start
     
   - This command will start the development server, and the web page will load!
     

**Access the Application:**
   - Once both the frontend (React) and backend (Flask) servers are running without errors, you can access your application by opening a web browser and navigating to the specified URL (usually `http://localhost:3000/` for React applications).


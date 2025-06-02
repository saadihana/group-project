FilterHub
Project Setup Guide
Prerequisites
Before running the project, ensure you have the following installed on your system:

Python (Latest stable version recommended)

Node.js & npm (Latest stable version recommended)

Backend Setup
Create and activate a virtual environment (recommended):

bash
Copy
Edit
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
Install required Python packages:

bash
Copy
Edit
pip install -r requirements.txt
If you don't have a requirements.txt file, you can install manually:

bash
Copy
Edit
pip install fastapi uvicorn pandas sentence-transformers torch python-multipart openpyxl pypapaparse
Navigate to the backend directory:

bash
Copy
Edit
cd backend
Run the backend server:

bash
Copy
Edit
python main.py
Frontend Setup
Navigate to the frontend directory:

bash
Copy
Edit
cd hackathon  # or your frontend folder name
Install Node.js dependencies:

bash
Copy
Edit
npm install
Run the frontend server:

bash
Copy
Edit
npm run dev
# or
npm start
Running the Full Project
To run both frontend and backend simultaneously:

Start the backend server in its folder:

bash
Copy
Edit
python main.py
Start the frontend server in its folder:

bash
Copy
Edit
npm run dev
Your application should now be up and running at the configured addresses.

Additional Notes
The venv folder is excluded from this repository. Please create your own virtual environment as shown above.

Make sure you have all dependencies installed to avoid runtime errors.

If you add any new packages, update the requirements.txt by running:

bash
Copy
Edit
pip freeze > requirements.txt

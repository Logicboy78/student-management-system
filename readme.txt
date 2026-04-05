                    STUDENT MANAGEMENT SYSTEM (Frontend Project)

-----------------------------------------------------------------------------------------------------
📌 Overview:
1. This is a simple Student Management System built using HTML, CSS (Tailwind), and JavaScript.
2. It allows users to add, edit, delete, and store student records directly in the browser using Local Storage.
-----------------------------------------------------------------------------------------------------

-----------------------------------------------------------------------------------------------------
✨ Features:
	•	Add new student details (Name, ID, Email, Contact)
	•	Edit existing student records
	•	Delete student records
	•	Form validation for accurate data entry
	•	Persistent storage using LocalStorage
	•	Initial data loading from JSON file (students.json)
	•	Responsive UI using Tailwind CSS
-----------------------------------------------------------------------------------------------------

-----------------------------------------------------------------------------------------------------
🛠️ Technologies Used:
	•	HTML5
	•	CSS3 (Tailwind CSS)
	•	JavaScript (Vanilla JS)
	•	Browser LocalStorage API
-----------------------------------------------------------------------------------------------------

-----------------------------------------------------------------------------------------------------
📂 Project Structure:

/project-folder
│
├── index.html        → Main UI structure
├── script.js         → Core logic (add/edit/delete/display)
├── students.json     → Initial dummy data
└── README.txt        → Project documentation
-----------------------------------------------------------------------------------------------------

-----------------------------------------------------------------------------------------------------
⚙️ How It Works:
	1.	On page load:
	•	Checks if data exists in LocalStorage
	•	If not, loads data from students.json
	2.	Form Submission:
	•	Validates input fields
	•	Adds or updates student data
	3.	Data Handling:
	•	Stored in LocalStorage
	•	Automatically updated after every operation
	4.	Table Rendering:
	•	Dynamically displays student data using JavaScript
-----------------------------------------------------------------------------------------------------

-----------------------------------------------------------------------------------------------------
🧪 Validations Applied:
	•	Name → Only alphabets allowed
	•	ID → Numbers only
	•	Contact → Minimum 10 digits
	•	Email → Proper email format
-----------------------------------------------------------------------------------------------------

-----------------------------------------------------------------------------------------------------
⚠️ Known Issues:
	•	“Unexpected end of JSON input” error may occur if:
→ students.json is empty
→ file path is incorrect
→ project is not running on a server
→ Try to empty the Cache(Using Inspect Option)
-----------------------------------------------------------------------------------------------------


-----------------------------------------------------------------------------------------------------
▶️ How to Run:

IMPORTANT: Do NOT open index.html directly

Use a local server:

Option 1 (VS Code):
	•	Install “Live Server” extension
	•	Right-click index.html → Open with Live Server

Option 2 (Python):
	•	Run command:
python -m http.server
	•	Open:
http://localhost:8000
-----------------------------------------------------------------------------------------------------

-----------------------------------------------------------------------------------------------------
📌 Future Improvements:
	•	Add search and filter functionality
	•	Connect to backend (Node.js / Express)
	•	Add database (MongoDB / MySQL)
	•	Implement authentication system
	•	Improve UI/UX with animations
-----------------------------------------------------------------------------------------------------

-----------------------------------------------------------------------------------------------------
👨‍💻 Author:
Gitansh Kashyap
-----------------------------------------------------------------------------------------------------
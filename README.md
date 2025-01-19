# task_tracker
A simple web application for tracking tasks with a grid-based layout using HTML, Tailwind CSS, and JavaScript. This app lets you add tasks, define start and end dates, and mark their completion for specific dates using a checkbox. Data is stored locally in the browser using localStorage.

Features
📅 Dynamic Grid Layout
Each task is displayed in a row, with corresponding dates as columns.
Dynamically generated columns based on task date ranges.
✅ Mark Task Completion
Use checkboxes to mark tasks as completed for specific dates.
Checked statuses are saved in localStorage for persistence.
💾 Data Persistence
Tasks and their statuses are stored locally in the browser.
📱 Responsive Design
Optimized for desktops and smaller screens.
Horizontal scrolling for large date ranges.


Getting Started

Installation
Clone this repository:
git clone https://github.com/1saptarshi/task_tracker.git
Navigate to the project directory:
cd task_tracker
Open the index.html file in your preferred web browser to launch the app.

Usage

Enter the Task Name, Start Date, and End Date in the form.
Click the "Add Task" button to add it to the grid.
Use the checkboxes in the grid to mark tasks as completed for specific dates.
All data is automatically saved locally in your browser.


File Structure

 task-tracker-grid/
│
├── index.html       # Main HTML file
├── README.md        # Documentation
├── LICENSE          # License file (MIT)
└── assets/          # Optional folder for images, icons, etc.


Roadmap

 Add editing and deleting tasks.
 Support exporting tasks (CSV or JSON format).
 Implement filtering or sorting by date range.
 Add dark mode.

Technologies Used

HTML: Markup for the web page.
Tailwind CSS: For modern styling and responsive design.
JavaScript: For grid generation and interactivity.
LocalStorage: To persist tasks and completion statuses.

License
This project is licensed under the MIT License.





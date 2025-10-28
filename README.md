# Assignment-8

### Overview
The Employee Management System allows users to view, add, and delete employees dynamically. All data is stored in a multi-dimensional array and displayed neatly within an HTML table.

### Features
- Displays a pre-loaded list of **5 employees** when the page loads.  
- Allows users to **add new employees** using input fields for:
  - **Name**
  - **Title**
  - **Extension**
- Performs **JavaScript validation** (no `required` attribute) to ensure that all fields are filled before adding an employee.
  - If a field is empty, a **red error message** appears next to it.
- Displays employees in a **structured table** with the following columns:
  - Name
  - Title
  - Extension
  - Delete button
- Includes a **delete** button for each employee row to remove them from the list.
- Automatically updates the **employee count** in the header (e.g., “Showing 5 Employees”) whenever employees are added or removed.

### Technologies Used
- **HTML5**
- **CSS3**
- **JavaScript (DOM scripting)**

### How It Works
1. On page load, the system displays the existing employees.
2. The user can fill out the form and click **Add Employee** to insert a new entry.
3. JavaScript validates input fields before adding the record.
4. Each employee row includes a **Delete** button to remove that employee.
5. The total number of employees updates automatically.

### Learning Reflection
This module helped me understand how **JavaScript connects the DOM and the BOM** to create interactive web applications. I also gained a better understanding of **asynchronous programming** using features like the Fetch API and **async/await**, which can improve performance and user experience in future projects.  



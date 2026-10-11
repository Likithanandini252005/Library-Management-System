# Library Management System

A desktop-based Library Management System developed using Python, PyQt5, and MySQL. The application helps manage books, authors, categories, publishers, library members, and daily book rental operations through a graphical user interface.

## Features

- **Book Management:** Add and manage book details.
- **Category Management:** Organize books by category.
- **Author Management:** Store and manage author information.
- **Publisher Management:** Maintain publisher details.
- **Member Management:** Manage library client records.
- **Book Issue and Return:** Record daily book rental and return operations.
- **Excel Reports:** Generate reports from library data.
- **User Authentication:** Login functionality and user management.
- **Themes:** Switch between different application themes.

## Technologies Used

- Python
- PyQt5
- MySQL
- MySQL Workbench
- Qt Designer
- CSS

## Project Structure

- `index.py` — Main application code.
- `library.ui` — Main user interface.
- `library2.ui` — Additional user interface.
- `icons/` — Application icons.
- `themes/` — Application theme stylesheets.
- `icons.qrc` — Qt resource configuration.
- `icons_rc.py` — Generated Qt resource module.
- `requirements.txt` — Python dependencies.

## Prerequisites

- Python installed on your system.
- MySQL Server running locally.
- A MySQL database named `library`.
- The database tables required by the application.

## Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/Likithanandini252005/Library-Management-System.git
   cd Library-Management-System
   ```

2. Install the Python dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Create and configure the MySQL database named `library`, including the tables required by the application.

4. Set your MySQL password as an environment variable.

   **Windows PowerShell:**

   ```powershell
   $env:DB_PASSWORD="your_mysql_password"
   ```

5. Start the application:

   ```bash
   py index.py
   ```

## Database Configuration

The application connects to MySQL on `localhost`, port `3306`, using the database name `library` and the `root` database account by default. The database password is read from the `DB_PASSWORD` environment variable.

The database schema is not included in this repository. You must create the required tables before running the application.

## Learning Outcomes

- Building desktop applications using Python and PyQt5.
- Designing interfaces with Qt Designer.
- Connecting Python applications to MySQL.
- Performing database operations such as inserting, retrieving, updating, and deleting records.
- Applying themes and styling to desktop interfaces.
- Generating Excel reports.

## Future Improvements

- Add a documented database setup script.
- Improve input validation and error handling.
- Add automated tests.
- Improve database security and user permissions.

## License and Attribution

If this project is based on or adapted from another developer's work, retain the original author's attribution and comply with the original project's license. Add the applicable license details here.

## Repository

[Library Management System on GitHub](https://github.com/Likithanandini252005/Library-Management-System)

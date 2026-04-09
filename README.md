# Library Management System

A web-based Library Management System built using PHP, MySQL, HTML, CSS, and JavaScript.  
This system allows students to browse books, request issues/returns, and enables admins to manage books, students, and transactions efficiently.

---


## Project Structure

### Root Directory
- `index.php` – Main landing page.
- `see.php` – View details or logs.
- `dbconn.php` – Database connection file.
- Folders:
  - `admin/` – Admin panel files.
  - `student/` – Student panel files.
  - `css/` – Stylesheets.
  - `images/` – All image assets.
  - `database/` – SQL files to setup the database.
  - `scripts/` – JS scripts for frontend interactions.

### Student Panel (`student/`)
- `book.php` – Browse books.
- `bookdetails.php` – Book detailed view.
- `current.php` – Current issued books for student.
- `edit_student_details.php` – Update student info.
- `findbook.php` – Search books.
- `history.php` – Issue history.
- `index.php` – Student dashboard.
- `issue_request.php` – Request a book issue.
- `logout.php` – Logout.
- `message.php` – View messages.
- `profile.php` – Student profile.
- `recommendations.php` – Recommended books.
- `renew_request.php` – Request book renewal.
- `return_request.php` – Request book return.
- `scripts/` – JavaScript for student functionalities.
- `css/` & `images/` – Custom styles and images for student portal.
- `bootstrap/` – Bootstrap framework for styling.

### Admin Panel (`admin/`)
- `addbook.php` – Add new books.
- `book.php` – Manage books.
- `bookdetails.php` – Book detail view.
- `current.php` – Current issued books.
- `dbconn.php` – Database connection for admin.
- `edit_admin_details.php` – Edit admin info.
- `edit_book_details.php` – Update book info.
- `findbook.php` – Search books.
- `findbookissue.php` – Search issued books.
- `finduser.php` – Search student/user.
- `index.php` – Admin dashboard.
- `issue_requests.php` – View issue requests.
- `logout.php` – Admin logout.
- `message.php` – Admin messages.
- `profile.php` – Admin profile.
- `recommendations.php` – Book recommendations.
- `reject.php` – Reject requests.
- `renew_requests.php` – Renewal requests.
- `requests.php` – View all requests.
- `return_requests.php` – Return requests.
- `student.php` – Manage students.
- `studentdetails.php` – Student details.
- `scripts/`, `css/`, `images/`, `bootstrap/` – Frontend assets.

### Database (`database/`)
Contains SQL scripts to setup the database:
- `LMS_author.sql`
- `LMS_book.sql`
- `LMS_message.sql`
- `LMS_recommendations.sql`
- `LMS_record.sql`
- `LMS_renew.sql`
- `LMS_return.sql`
- `LMS_user.sql`

---

## Features

- Admin can add, edit, and delete books and manage student accounts.
- Students can browse, search, request issues, renewals, and returns.
- Student and admin dashboards for monitoring activities.
- Messaging system between admin and students.
- Book recommendations and history tracking.
- Fully responsive UI with Bootstrap and custom CSS.

---

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Prasanth-malla/library_management_system.git

2. Import SQL files from database/ folder into MySQL to create the database.

3. Configure dbconn.php with your MySQL credentials.

4. Open the project in a local server (e.g., XAMPP or WAMP).

5. Access via browser:

   Admin: http://localhost/library_management_system/admin/index.php
   
   Student: http://localhost/library_management_system/student/index.php

Contact

Email: mallaprasanth1234@gmail.com

LinkedIn: https://www.linkedin.com/in/prasanthmalla-softwareengineer/

GitHub: https://github.com/Prasanth-malla

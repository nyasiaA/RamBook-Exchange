# RamBook Exchange

**For Rams. By Rams.**

## Project Overview

RamBook Exchange is a web application designed for students at Winston-Salem State University (WSSU). The platform allows students to buy, sell, and trade textbooks with other students. It also includes a proposed contactless textbook return system to help make the return process more convenient.

This is an unofficial student software engineering project and is not an official WSSU bookstore service.

## Project Features

- Student registration and login
- Browse and search available textbooks
- List textbooks for sale or trade
- View textbook details
- Send purchase or trade requests
- Manage textbook listings through a student dashboard
- Schedule textbook returns
- Generate return confirmation codes
- Track textbook return status
- Bookstore administration interface for managing returns

Some features are still being integrated and tested.

## Technologies Used

**Frontend**
- HTML
- CSS
- JavaScript

**Backend**
- Python
- Flask
- Flask-SQLAlchemy
- Flask-Login

**Database**
- SQLite (local development)
- PostgreSQL (cloud deployment)

**Development Tools**
- Visual Studio Code
- Git and GitHub
- Docker
- Render

## Project Structure

```text
RamBook-Exchange/
│
├── app.py
├── requirements.txt
├── README.md
│
├── templates/
│   ├── index.html
│   ├── marketplace.html
│   ├── add_book.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── book_details.html
│   ├── return_books.html
│   ├── return_status.html
│   └── bookstore_admin.html
│
└── static/
    └── style.css
```

Additional files may be added as development continues.

## How to Run the Project

**1. Clone the GitHub repository**

```bash
git clone https://github.com/trenadi27/RamBook-Exchange.git
```

**2. Open the project folder**

```bash
cd RamBook-Exchange
```

**3. Install the required Python packages**

```bash
pip install -r requirements.txt
```

**4. Start the Flask application**

```bash
python app.py
```

**5. Open the website**

Visit:

http://127.0.0.1:5000

The application currently uses a local SQLite database for development.

## Team Responsibilities

**Person 1 – Frontend Development**
- Designed the website layout and navigation
- Created HTML pages
- Styled the website using CSS
- Worked on connecting frontend pages to Flask routes

**Person 2 – Backend Development**
- Developed Flask routes
- Implemented student registration and login
- Created textbook listing and exchange functionality
- Developed return scheduling and tracking logic
- Created database models

**Person 3 – Database and Deployment**
- Responsible for PostgreSQL configuration
- Responsible for Docker containerization
- Responsible for cloud deployment
- Responsible for deployment testing

## Current Project Status

The frontend pages and Flask backend have been created. Frontend and backend integration is underway, and additional functionality and security testing are still needed.

PostgreSQL integration, Docker containerization, and cloud deployment through Render have been completed. The Docker image was successfully built and tested.

## GitHub Repository

https://github.com/trenadi27/RamBook-Exchange

## Disclaimer

RamBook Exchange is an academic software engineering project. It is not affiliated with or officially endorsed by Winston-Salem State University.

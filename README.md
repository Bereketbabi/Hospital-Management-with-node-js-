# Hospital Management System

## Overview
This is a **Hospital Management System** built using **Node.js, Express, and MySQL**. It allows hospitals to manage doctors, appointments, employees, complaints, and chat systems.

## Features
- **Doctor Management**: Add, update, and remove doctor details.
- **Appointment Scheduling**: Manage patient appointments.
- **Employee Management**: Handle hospital employees.
- **Complaint Management**: Record and track complaints.
- **Authentication**: User login and authentication system.

## Installation
### Prerequisites
Ensure you have the following installed:
- Node.js
- MySQL

### Steps
1. Clone the repository:
   ```sh
   git clone <repository-url>
   cd Hospital-Management-Using-NodeJs-Mysql-Express
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Set up the database:
   - Create a MySQL database.
   - Import `nodelogin.sql` into your MySQL database.
4. Configure environment variables:
   - Create a `.env` file and add database credentials.
5. Start the server:
   ```sh
   npm start
   ```

## Folder Structure
```
Hospital-Management-Using-NodeJs-Mysql-Express/
├── controllers/         # Business logic controllers
├── routes/              # Route definitions
├── views/               # Frontend templates
├── public/              # Static files (CSS, JS, Images)
├── config/              # Database connection settings
├── app.js               # Main application entry point
├── package.json         # Project dependencies
├── nodelogin.sql        # Database schema
```

## Usage
- Access the system at `http://localhost:3000`
- Use login credentials from the database or register a new user.

## Technologies Used
- **Backend**: Node.js, Express.js
- **Database**: MySQL
- **Frontend**: HTML, CSS, JavaScript (if applicable)

## Contributing
Pull requests are welcome. For major changes, please open an issue first.

## License
This project is open-source and free to use.


# Tour-Package-Management-System
This project is a Tour Package Management System built using Node.js, Express, Ejs and MySQL. It allows customers to browse and book tour packages, while administrators can manage packages, view customer bookings, and update/delete packages.
# Features
# Customer:
Browse available tour packages.
Book a tour package.
View booking confirmation.
# Admin:
Add, update, and delete tour packages.
View all customer bookings.
Search and filter tour packages
# Installation
Prerequisites
Node.js and npm installed
MySQL installed
Git (for version control)
# Tech Stack
Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express
Database: MySQL
View Engine: EJS (Embedded JavaScript)
Other: dotenv for environment variables

# Run Locally
Clone the project<br>

  git clone https://github.com/N1nadLad/Tour_Package_Management_System<br>
Go to the project directory<br>

  cd Tour_Package_Management_System<br>
Install dependencies<br>

  npm install<br>
Start the server<br>

  node app.js<br>

# Database Schema
# Customers:

customer_id (Primary Key)
first_name
last_name
email
# TourPackages:

package_id (Primary Key)
package_name
description
destination
price
duration
start_date
end_date
# Bookings:

booking_id (Primary Key)
customer_id (Foreign Key references Customers.customer_id)
package_id (Foreign Key references TourPackages.package_id)
booking_date
# Environment Variables
To run this project, you will need to add the following environment variables to your .env file

MYSQL_HOST = 'localhost'

MYSQL_USER = 'your_username_here'

MYSQL_PASSWORD = 'your_password_here'

MYSQL_DATABASE = 'your_dbname_here'

PORT = your_portNum_here
<h3>Screenshots</h3>
<img width="1254" height="696" alt="Screenshot 2025-10-07 171048" src="https://github.com/user-attachments/assets/1d02b588-17cd-40a6-9ef3-926ed7fbc9d6" />
<img width="1242" height="770" alt="Screenshot 2025-10-07 171128" src="https://github.com/user-attachments/assets/57c018a1-23b4-4bdf-9773-8ffa94a6a5a8" />
<img width="1243" height="685" alt="Screenshot 2025-10-07 171144" src="https://github.com/user-attachments/assets/b985961a-de39-4735-b87b-3fa982f4fb5d" />
<img width="1256" height="696" alt="Screenshot 2025-10-07 171212" src="https://github.com/user-attachments/assets/b20a9591-4b39-45ca-a8d5-1c4a48513aee" />
<img width="1239" height="698" alt="Screenshot 2025-10-07 171226" src="https://github.com/user-attachments/assets/76286672-2620-470f-8d55-0134625046af" />

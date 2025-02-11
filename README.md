# 🚌 Bus Booking System

## 📌 Overview
The **Bus Booking System** is a web-based application built using **PHP and SQL**, designed to facilitate online bus ticket reservations. It allows users to **search, book, and manage bus tickets** conveniently.

## 📂 Features
- **User Registration & Login**
- **Search for Buses** (by route, date, and time)
- **Seat Selection & Booking**
- **Admin Panel** for bus management
- **Payment Integration** (Optional)
- **Booking History & Ticket Cancellation**

## 🔧 Technologies Used
- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Backend:** PHP
- **Database:** MySQL

## 🚀 Installation & Setup
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/yourusername/bus-booking-app.git
cd bus-booking-app
```
### 2️⃣ Setup Database
- Create a MySQL database.
- Import the `database.sql` file located in the project folder.
- Update database credentials in `config.php`:
```php
$host = 'localhost';
$user = 'root';
$password = '';
$database = 'bus_booking';
```

### 3️⃣ Start the Server
- If using **XAMPP**, move the project folder to `htdocs`.
- Start Apache and MySQL from the XAMPP Control Panel.
- Open the browser and go to:
  ```
  http://localhost/bus-booking-app/
  ```

## 📈 Database Structure
### Tables Used:
- **users** (User authentication & profile)
- **buses** (Bus details like route, timing, and availability)
- **bookings** (User bookings & transaction history)
- **payments** (Stores payment transactions, if integrated)

## 🔥 Future Improvements
- Implement **real-time seat availability** updates.
- Add **SMS/Email notifications** for booking confirmation.
- Integrate **online payment gateways**.
- Enhance UI/UX with **modern design**.

## 🤝 Contributing
Feel free to contribute by submitting pull requests! If you find bugs or have feature requests, create an issue.

## 📜 License
This project is open-source and available under the MIT License.

## 📬 Contact
For queries, reach out at [yourwebsite.com](https://yourwebsite.com).



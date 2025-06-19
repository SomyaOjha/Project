#  Hotel Management System with Face Recognition

This Hotel Management System is an advanced solution built using **Python (Tkinter)** for the GUI, **MySQL** for data storage, and **OpenCV + face recognition** for biometric authentication. It streamlines hotel bookings, customer records, and payment systems with enhanced security.

---

##  Key Features

- **Face Recognition for Security**: Only authorized personnel can log in using real-time facial authentication via OpenCV and face_recognition libraries.
- **Room Booking System**: Collects customer info (name, phone, check-in/out dates, room type), auto-assigns room, and generates unique customer IDs.
- **Restaurant Service Info**: Displays menu and prices for ordering food.
- **Automated Payments**: Calculates charges based on room type and stay duration.
- **Customer Records**: All bookings displayed in a searchable treeview.
- **Room Information**: Shows available rooms and prices.
- **Modern GUI**: Built with Tkinter for ease of use and clean visuals.

---

##  What Makes It Special?

-  **Biometric Access**: Adds a security layer using face recognition.
-  **Automated Room & ID Assignment**: Simplifies hotel operations.
-  **Custom Payment Module**: Automatically calculates charges.
-  **MySQL Integration**: Real-time, scalable database support.
-  **Pillow Integration**: Handles images for interface visuals and face data.

---

## Technologies Used

- Python
- Tkinter
- OpenCV & face_recognition
- MySQL
- Pillow (for image processing)

---

##  Setup Instructions

### 1. Install Required Libraries

```bash
pip install opencv-python face-recognition mysql-connector-python Pillow

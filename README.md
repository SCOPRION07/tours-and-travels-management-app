# Tours-and-Travels-Management-app
This repository contains the Tours and Travels Management App built for a college project. The app helps users explore tourist destinations, view hotels, check transportation options, and make bookings. The app is developed in Java for Android and integrates with a MySQL database.

**Features**--

**1. User Authentication:** Secure login and signup with user details stored in the database.

**2. Place Details:** Explore descriptions, attractions, and best times to visit for various destinations.

**3. Hotels and Transport:** View available hotels and transportation options specific to a selected place.

**4. Booking Management:**

Hotel selection with detailed rate and room type display.
Payment functionality with transaction history stored in the database.

**5. SQLite Integration:** Offline support using SQLite database for user data.

**How to Run the Project**--

**Prerequisites**

1. Android Studio installed.
   
2. MySQL Workbench installed for database management.
   
**Steps to Set Up**

1. Clone the repository.  (https://github.com/SCOPRION07/tours-and-travels-management-app.git)

2. Import the Android app zip file (dbms_app.zip) into Android Studio.
  
3. Import the SQL dump into MySQL Workbench.
 
4. Initialize the database using the provided CSV files for each table.

5. Update the database connection string in the app (connectionclass.java ) to match your MySQL credentials.
  Change the database name, username, and password according to your settings in MySQL Workbench
6. Run the app on an emulator or Android device.

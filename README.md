# ⏱️ Time Table Generator (PHP)

<div align="center">



[![GitHub stars](https://img.shields.io/github/stars/HAbhishekBhat/Time_Table_Generator_PHP?style=for-the-badge)](https://github.com/HAbhishekBhat/Time_Table_Generator_PHP/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/HAbhishekBhat/Time_Table_Generator_PHP?style=for-the-badge)](https://github.com/HAbhishekBhat/Time_Table_Generator_PHP/network)
[![GitHub issues](https://img.shields.io/github/issues/HAbhishekBhat/Time_Table_Generator_PHP?style=for-the-badge)](https://github.com/HAbhishekBhat/Time_Table_Generator_PHP/issues)
[![GitHub language](https://img.shields.io/github/languages/top/HAbhishekBhat/Time_Table_Generator_PHP?style=for-the-badge)](https://github.com/HAbhishekBhat/Time_Table_Generator_PHP)

**A PHP-based application for generating timetables.**

</div>

## 📖 Overview

This project provides a web application built using PHP to generate timetables.  It appears to utilize external files (`.txt` files) to define courses, rooms, and other constraints.  A database (`timetable.sql`) is also included, suggesting a persistent storage mechanism. The project also includes a Python script (`Bipartite_Matching_Assignment.py`), indicating the potential use of a bipartite matching algorithm for timetable optimization.  The primary functionality is to create a timetable based on the input data provided in these external files.  Further investigation into the PHP code within `Admin` folder (currently a zipped archive) would be needed for a complete understanding of the web application's features.

## ✨ Features

Based on the provided file names and structure, the application likely features:

- Course Management: Input and management of course details.
- Room Allocation: Assignment of courses to available rooms.
- Time Slot Management: Definition and utilization of time slots for classes.
- Constraint Handling: Consideration of conflicts and constraints during timetable generation.
- Timetable Generation: Automatic generation of a timetable based on the defined data and constraints.
- Database Integration: Persistent storage of timetable data and possibly course/room information.
- User Interface: A web-based interface for managing data and viewing the generated timetable.

## 🖥️ Screenshots




## 🛠️ Tech Stack

- **Backend:** PHP
- **Database:** MySQL (indicated by `timetable.sql`)
- **Algorithm:**  Likely uses a Bipartite Matching algorithm (Python script `Bipartite_Matching_Assignment.py`)


## 🚀 Quick Start

This section needs more detail as the exact implementation within the `Admin` folder is currently unknown.  The instructions below are preliminary and based on the external files and their usage within the Python script.

### Prerequisites

- A web server with PHP support (e.g., Apache, Nginx).
- MySQL database server.
- PHP MySQLi extension.
- Python 3 (for optional optimization script).

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/HAbhishekBhat/Time_Table_Generator_PHP.git
   cd Time_Table_Generator_PHP
   ```

2. **Database Setup:**
   Create a MySQL database and import `timetable.sql`.  Adjust database credentials as needed.

3. **Admin Folder Extraction:** Extract the `Admin.zip` file to access the core PHP application files.

4. **Configure Web Server:**  Configure your web server (Apache or Nginx) to serve the contents of the extracted `Admin` folder.

5. **Input File Preparation:** Prepare the input files (`course_file.txt`, `room_file.txt`, `slot_file.txt`, `room_occupancy_file.txt`, etc.) with the appropriate data format.  The format of these files is not specified and would require further investigation into the PHP application to be accurately defined.

6. **Run the Application:** Access the application through your web browser.


## 📁 Project Structure

```
Time_Table_Generator_PHP/
├── AboutUs.php
├── Admin/              (Contains core PHP application - currently zipped)
├── Admin.zip
├── Bipartite_Matching_Assignment.py
├── ContactUs.php
├── ForPass.php
├── Forget.php
├── Header.php
├── homepage.png
├── index.php
├── input_graph.txt
├── login.php
├── meIIIsem.php
├── meIIIsem.txt
├── meVIIsem.txt
├── meVsem.txt
├── menu.php
├── new.c
├── output_graph.txt
├── right.php
├── room_file.txt
├── room_occupancy_file.txt
├── slot_file.txt
├── temp
├── text.cpp
├── timetable.sql
├── tt.c
├── tt.exe
└── tt/
```



## 📄 License
This project is licensed under the MIT License – you are free to use, modify, and distribute.


---

<div align="center">

**⭐ Star this repo if you find it helpful!**

</div>

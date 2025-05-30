# Interview-Nest

**Interview-Nest** is a pre-configured, portable development environment based on [XAMPP](https://www.apachefriends.org/index.html). It bundles Apache, MySQL, PHP, Tomcat, and other useful tools for offline and local development purposes — especially tailored for interviews, testing, or quick PHP-based project demos.

## ✨ Features

- **Apache** 2.4.58
- **MariaDB** 10.4.32
- **PHP** 8.2.12 (with PEAR)
- **phpMyAdmin** 5.2.1
- **Tomcat** 8.5.96
- **FileZilla FTP Server**
- **Mercury Mail Transport System**
- **Strawberry Perl** 5.32.1.1 Portable
- **XAMPP Control Panel** 3.3.0
- Batch scripts for easy startup/shutdown of services

## 🚀 Getting Started

1. **Install Prerequisites**
   - [Microsoft Visual C++ 2019 Redistributable](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist) is required for PHP to run.
   
2. **Run the Stack**
   - Use the following `.bat` files to control services:
     - `apache_start.bat` / `apache_stop.bat`
     - `mysql_start.bat` / `mysql_stop.bat`
     - `filezilla_start.bat` / `filezilla_stop.bat`
     - `mercury_start.bat` / `mercury_stop.bat`
     - `catalina_start.bat` / `catalina_stop.bat` (for Tomcat)

3. **Configuration**
   - Modify `properties.ini` to adjust default settings.
   - Default login credentials (if any) are listed in `passwords.txt`.

4. **Accessing Services**
   - Visit `http://localhost` after starting Apache.
   - Use `http://localhost/phpmyadmin` for database management.

## 🧪 Useful Scripts

- `killprocess.bat`: Force-stop all services.
- `setup_xampp.bat`: Initial setup and configuration script.
- `ctlscript.bat`: Central control script for all services.

## 📁 Folder Structure
Interview-Nest-main/
├── apache_start.bat
├── mysql_start.bat
├── filezilla_start.bat
├── mercury_start.bat
├── catalina_start.bat
├── passwords.txt
├── properties.ini
└── ...


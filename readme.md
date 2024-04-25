**LAMP Stack** is a powerful combination of four open-source technologies that web developers use to build websites and web applications but with my **NG Edition** that support Debian, RPM, Arch and SUSE Bases, it comme with more components like:
- composer,
- firewall,
- php-common,
- ...

### Requiered :
- **Linux**: The **operating system** layer.

### We'll install:
1. **Apache/Httpd**: The **web server** layer. Apache serves as the bridge between the user's browser and the backend application. It handles requests, processes them, and delivers web content to users.

2. **MySQL/MariaBD**: The **database server** layer. It's where information like user profiles, product details, and other dynamic content resides. Developers use SQL queries to interact with the database.

3. **PHP**: The **programming language** layer. PHP is a server-side scripting language. It processes requests, interacts with the database, and generates dynamic web pages. It's commonly used for building web applications.

### Optionnaly
4. **phpMyAdmin**: a **free and open-source administration tool** designed for managing **MySQL** and **MariaDB** databases. Written primarily in **PHP**, it provides a web-based interface for various database operations like:

    - **Database Administration**: You can perform common tasks such as creating, copying, dropping, renaming, and altering databases, tables, fields, and indexes.

    - **SQL Execution**: phpMyAdmin allows you to execute and edit SQL statements directly. You can also bookmark frequently used queries.

    - **User Account Management**: Manage MySQL user accounts and their privileges.

    - **Import and Export Data**: Import data from CSV and SQL files, and export data to various formats including CSV, SQL, XML, PDF, and more.

    - **Visual Database Layout**: Create graphics representing your database schema in different formats.

5. **Composer** is an **open-source dependency management tool** for **PHP**.

6. **Firewall**: securing servers access

7. **php-common**: a package that includes common files for PHP packages. It contains utilities shared among all packaged PHP versions.

8. more features coming soon ...

### How-to MySQL DB Configurations

- **Creating a `root` users** <br>
CREATE USER 'root'@'%' IDENTIFIED BY 'root'; <br>
GRANT ALL PRIVILEGES ON *.* TO 'root'@'%' WITH GRANT OPTION;
<br><br>

- **Remove anonymous users** <br>
DROP USER 'anonymous';
<br><br>

- **Remove test database and access to it** <br>
DROP DATABASE 'test';
<br><br>

- **Reload privilege tables** <br>
FLUSH PRIVILEGES;

#### Tested on:
- fedora 38/39

<hr>

- **Full Changelog**: [here](https://github.com/bebagodfried/lampp-ng/compare/v1.0-beta.2...v1.1)

- **Feedback** 
Please report issues and feature requests [here](https://github.com/bebagodfried/lampp-ng/issues).

<hr>

**<u>License</u>**: [MIT License](https://github.com/bebagodfried/lampp-ng/blob/3818009932ae7276ab021e1eff83153924948cf3/license) |
**<u>Author</u>**: [Béba Godfried A.](dev@bebagodfried.com)

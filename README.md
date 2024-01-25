## Bar & Restaurant ERP 
Complete Restaurant Management ERP
Adam's Ale Restaurant ERP is a web application built using CodeIgniter 4, designed to help restaurant owners manage their business operations more efficiently. With Adam's Ale Restaurant ERP, restaurant owners can manage their menus, tables, orders, and inventory all in one place.

<p align="center"> 
<img src="http://adamsale.xcommercex.com/images/logo2.png" width="350" style="max-width: 100%;margin:20px 0 0 200px"/>
</p>
## Features
Menu management: Add, edit, and delete menu items, and organize them by category.
Table management: Create, edit, and delete tables, and assign orders to tables.
Order management: Create, edit, and delete orders, and view their status.
Inventory management: Track inventory levels for each menu item, and receive alerts when inventory levels are low.
User management: Add, edit, and delete users, and assign roles and permissions

## Live Demo 
 ```sh
   Executive Login | http://adamsale.xcommercex.com/executive
   Credentials : executive/executive
   
    Managerial Login | http://adamsale.xcommercex.com/managerial
    Credentials : managerial/managerial
    
    Staff Login | http://adamsale.xcommercex.com/staff
    Credentials : staff/staff
   
   Super Admin Login | http://admin.adamsale.xcommercex.com/
   Credentials : superadmin/superadmin
```
## Prerequisites
PHP 7.3 or higher
MySQL 5.7 or higher
Apache web server

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._


1. Clone the repo - For Local
  ```sh
   Install latest version of XAMPP
   ```
   ```sh
   c:/folder > git clone https://github.com/algobasket/AdamsAle-Restaurant.git
   c:/folder>cd AdamsAle-Restaurant
   c:/folder/AdamsAle-Restaurant>php spark serve

   Go to https://localhost:8080/
   ```
   Clone the repo - For LIVE
   ```sh
   public_html / (Root Folder) > git clone https://github.com/algobasket/AdamsAle-Restaurant.git .
   ```
2. Change settings inside .env
   ```sh
    CI_ENVIRONMENT = production
    app.baseURL = 'https://YOUR-SITE.com/'

   database.default.hostname = localhost
   database.default.database = DATABASE NAME
   database.default.username = DATABASE USERNAME 
   database.default.password = DATABASE PASSWORD
   database.default.DBDriver = MySQLi
   database.default.DBPrefix =
   database.default.port = 3306
   ```

   ```sh
    public_html > php spark migrate 
    ```

   ```sh
    find -type f | xargs chmod 644 ; find -type d | xargs chmod 755 ; chmod 750 . -c

    or

    find ./ -type f -not -perm 644 -not -name ".ftpquota" -exec chmod 644 -c {} \;; find ./ -type d -not -perm 755 -not -group nobody -exec chmod 755 -c {} \;
    ```
 3. Auto update earning using Cron (Mon - Fri)
   ```sh
    https://YOUR-SITE.com/CronTaskForInventory
   ```
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License
This project is build by Algobasket.

## Support
For future updates, please click that sponsor button on my profile
https://github.com/sponsors/algobasket 

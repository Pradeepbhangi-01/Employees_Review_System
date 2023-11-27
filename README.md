# Employees_Review_System

A full stack app, in which the admin, can assign the employees, to review each other on the basic of there work. The admin has special power, to make any other employee as the new admin. Admin can also make the new employee, and they can also assing, the reviewer and revieweee. The admin can see the current employee, and according to the review, the admin can remove the employee. The review given to the employee, is always going to be store in the database.

# Tech Stack
Node , Express, Mongodb , EJS , javaScript , html, css

# Featuers
You can review the employees. The admin has the special power to assing the task to employee, remove the employee, make employee as admin and add new employee;

# Folder Structure Employee_Review_System


    |
    |               |--->css
    |--->assets---->|--->images
    |             
    |
    |               |--->flashMiddleware.js
    |--->config---->|--->mongoose.js
    |               |--->passport-local-Stradegy.js
    |
    |                  |-->admin_controller.js
    |--->controllers-->|-->home_controller.js
    |                  |-->review_controller.js
    |                  |-->user_controller.js
    |
    |               |-->review.js
    |--->models---->|
    |               |-->user.js
    |
    |              
    |               |-->admin.js
    |--->routes---->|-->index.js
    |               |-->review.js
    |               |-->user.js
    |
    |              |--->_header.ejs
    |              |---> addEmployee.ejs
    |              |---> admin.ejs
    |              |---> employe.ejs
    |--->views---->|--->forgot_password.ejs
    |              |--->home.ejs
    |              |--->layout.ejs
    |              |--->sign_in.ejs
    |              |--->sign_up.ejs
    |
    |-->node_modules
    |-->.gitignore
    |--> index.js
    |--> package-lock.json
    |-->package.json
    
    ````



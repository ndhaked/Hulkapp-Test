Hulk App Interview Task (Laravel V 8.12)
## Getting Started

This Project is created in Laravel framwork as a purpose of Test interview Practical Task.



### Prerequisites

Application is built with Laravel 8.12 as php framework and MySQL database is used for db operation.

### Server Requirment
	- Php 7.3 or Greater
	- mysql

### Installing

A step by step series of examples that tell you how to get a development env running.
- First clone this project
- Run composer update
- Set configuration in .env file like database setting and your app url
- Import mysql in database
- composer update
- npm install
- Run dump autoload
- Run php artisan serve
- Run php artisan storage:link
- Open http://127.0.0.1:8000

### Set Following details in .env for email notification
MAIL_DRIVER=smtp
MAIL_HOST=smtp.gmail.com
MAIL_PORT=587
MAIL_USERNAME=testindi21@gmail.com
MAIL_PASSWORD=zswyvklfqnpnedjw
MAIL_FROM=no-reply@demo.com
MAIL_NAME=Laravel
MAIL_FROM_NAME="${APP_NAME}"
MAIL_FROM_ADDRESS=no-reply@demo.com
MAIL_ENCRYPTION=tls

### Please also add these details in .env for api
API_STANDARDS_TREE=vnd
API_SUBTYPE=myapp
API_PREFIX=api
API_VERSION=v1
API_NAME=API
API_CONDITIONAL_REQUEST=false
API_STRICT=false
API_DEFAULT_FORMAT=json
API_DEBUG=true
API_APIAUTHMD5=
JWT_SECRET=CapZQLHv1Zc2j0LLoMDHZQ8ydxhThQ07CQZE1ERuAwJL6WQP08tjkCY3vWTpS4xO


### Admin Login Details
URL: http://127.0.0.1:8000/admin/login
Email: hulkapp@yopmail.com
Password: 12345678


### Exam Details (Option 1:Dynamic Forms)
Question: 
### System will have two types of users
	○ Admin
	○ Normal User
Answer : Please check Following Url: 
	Step 1: Please Login With Admin then open followinf url from sidebar
	URL: http://127.0.0.1:8000/admin/roles

### Admin should be able to create form definitions where admin will specify fields and validation rules.
	● User should be able to fill the forms with all specified validation rules
		○ Min
		○ Max
		○ Email
Answer : Please check Following Url: 
	Step 1: Please Login With Admin then open following url from sidebar
	URL: http://127.0.0.1:8000/admin/forms
		This is Form Manager where we can create a dynamic form after then we create form fields dynamic Validiation Rules from following Manager: -
			URL: http://127.0.0.1:8000/admin/formfields	
### Users can fill out forms only once.
Answer : For this form first user need to register from frontend as a user role then agter login with user role he got a dyanamic form in header menu with dyanamic validiation rules set by admin once he submitted dyanamic form he dont able to re-submit form his same account. please check on this Url;

User Login Url: http://127.0.0.1:8000/login
Dynamic Form URL After User Login: http://127.0.0.1:8000/forms/feedback

### Admin should be able to access state of form
		○How many times it was submitted
		○How many times it was opened.
Answer : Please check Following Url: 
	URL: http://127.0.0.1:8000/admin/dashboard

	QUestion: Which user submitted what answers
	Answer: Please check these details on every user Details Page sepratly from users listing page click on action view button.




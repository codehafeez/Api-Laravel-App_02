# API Postman - Laravel API Example using Multiple Tables

[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.codehafeez.com/)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/codehafeez/)

[![whatsapp](https://img.shields.io/badge/whatsapp-GREEN?style=for-the-badge&logo=whatsapp&logoColor=white)](https://api.whatsapp.com/send?phone=923123349398)



```bash
# -------------------------------------------------------------------
# Step1
# -------------------------------------------------------------------
laravel new hafeez-app
cd hafeez-app
php artisan serve



# -------------------------------------------------------------------
# Step2
# -------------------------------------------------------------------
php artisan make:controller EmployeeController
php artisan make:controller SalaryController

php artisan make:model Employee -m
php artisan make:model Salary -m

php artisan migrate



php artisan serve
http://127.0.0.1:8000/api/addEmployee
http://127.0.0.1:8000/api/addSalary
http://127.0.0.1:8000/api/getData
http://127.0.0.1:8000/api/getDataJoin
http://127.0.0.1:8000/api/getDataHasOne
```    


## Screenshots
![](https://raw.githubusercontent.com/codehafeez/Api-Laravel-App_01/main/Screenshots/Output-01.png)


## 🔗 www.codehafeez.com

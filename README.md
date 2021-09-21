## Laravel Developer Assessment
This application is built with the following technologies:
1. HTML
2. CSS,
3. Bootstrap(3.3.7)
4. Jquery(1.12.4)
5. AjAX
6. PHP(7.3.29) and Apache/2.4.48
7. Laravel Framework(7.18.0)
7. MYSQL(5.0.12)
8. Google Fonts(Roboto|Varela+Round, & Material+Icons)
9. Font-awesome(4.7.0)
10.Composer version 2.1.3 2021-06-09 16:31:20
11. XAMPP(7.3.29)

### System re
1. Laravel 5.6
2. Materialize
3. Admin BSB Material Design


### This is how you can install this application
01. Clone this Repository(Repo) with the following command `git clone https://github.com/Bonifaceebuka/datamax-registrars-assessment.git`
02. Move to the DIR of the Repo `cd datamax-registrars-assessment`
03. Install composer with `composer install`
04. Save .env.example file to .env or run this command: `cp .env.example .env`
	Open the .env file and set the Database configurations as follows:
	DB_CONNECTION=mysql
	DB_HOST=127.0.0.1
	DB_PORT=3306
	DB_DATABASE=YOUR_DATABASE_NAME
	DB_USERNAME=YOUR_SERVER_USERNAME
	DB_PASSWORD=YOUR_DATABASE_PASSWORD (Leave it empty if you have none)
05. Generate new Key with this command: `php artisan key:generate`
06. Import the database tables with this command: `php artisan migrate`
09. Start your server with `php artisan serve`
	Visit localhost::8000/ to see the front-end of the application


### Screenshot

<img src="https://github.com/parvez-git/real-estate/blob/master/public/demo/home.jpg">
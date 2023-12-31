Metamata Challenge - Arif
This repository contains my submission for the Metamata Challenge.

Installation
To install the application, follow these steps:

Clone the repository to your local machine:
git clone https://github.com/arifrhm/metamata-challenge-arif.git


Navigate to the project directory and install the dependencies:
cd metamata-challenge-arif
composer install


Copy the .env.example file to .env:
cp .env.example .env


Generate a new application key:
php artisan key:generate


Set up your database by editing the DB_DATABASE, DB_USERNAME, and DB_PASSWORD variables in the .env file.


Run the database migrations and seed the database with test data:

php artisan migrate --seed


Start the development server:
php artisan serve
The application should now be running on http://localhost:8000.

Usage
To use the application, navigate to http://localhost:8000 in your web browser. From there, you can view and interact with the application.

Contributing
If you would like to contribute to the project, please follow these steps:

Fork the repository.

Create a new branch for your changes:
git checkout -b feature/my-new-feature

Make your changes and commit them:
git commit -am 'Add some feature'

Push your changes to your fork:
git push origin feature/my-new-feature

Create a new pull request.

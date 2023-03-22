# Laravel 8 CRUD Application

This is a simple CRUD (Create, Read, Update, Delete) operation application built using Laravel 8 PHP framework. The application allows you to perform CRUD operations on a "companies" table, where you can add, edit, delete, and view company records.

## Installation
1. Clone the repository to your local machine: `git clone https://github.com/your-username/LaravelCRUD.git`
2. Install the dependencies: `composer install`
3. Create a copy of the `.env.example` file and rename it to `.env`. Update the `.env` file with your database details.
4. Generate the application key: `php artisan key:generate`
5. Run the database migrations to create the required tables: `php artisan migrate`
6. Start the development server: `php artisan serve`

## Usage
After completing the installation steps, you can use the application to perform CRUD operations on the "companies" table. The available routes are:

- GET /companies - display all companies
- GET /companies/create - display the form to create a new company
- POST /companies - store the new company in the database
- GET /companies/{id}/edit - display the form to edit an existing company
- PUT/PATCH /companies/{id} - update the company in the database
- DELETE /companies/{id} - delete the company from the database

## Contributing
If you would like to contribute to this project, please follow these steps:

1. Fork the repository
2. Create a new branch for your feature: `git checkout -b feature-name`
3. Commit your changes: `git commit -m "add feature-name"`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request to the main repository

## Credits
This application was built following the tutorial by [Your Name] on [Link to tutorial].

## License
This project is licensed under the MIT License - see the LICENSE file for details.

# Person Management API with Laravel

This project is an API built with Laravel for managing people's information. It provides endpoints to add and retrieve persons' data and uses MySQL to store the information.

## Features

- **REST API**: Provides RESTful endpoints for managing persons, including adding and retrieving data.
- **MySQL Database**: Uses MySQL as the database to store persons' information securely.
- **Code Structure**: Follows clear and maintainable code structure following Laravel best practices.
- **Endpoint Security**: Implements security measures to secure the API endpoints and protect sensitive data.

## Technologies Used

- Laravel: PHP framework for building web applications and APIs.
- MySQL: Relational database management system for storing data securely.

## Installation

1. Clone the repository: `git clone https://github.com/HaithemHadjAmmar/test_laravel_project.git`
2. Navigate to the project directory: `cd test_laravel_project`
3. Install composer dependencies: `composer install`
4. Copy the `.env.example` file to `.env` and configure your database settings
5. Generate application key: `php artisan key:generate`
6. Run database migrations: `php artisan migrate`

## Usage

1. Start the Laravel development server: `php artisan serve`
2. The API is now accessible at `http://localhost:8000`
3. You can use API client tools like Postman or curl to interact with the endpoints.

## API Documentation

The API provides the following endpoints:

- `POST /api/persons`: Adds a new person to the database.
- `GET /api/persons`: Retrieves the list of persons from the database.

For detailed API documentation and endpoint security considerations, refer to the API documentation.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

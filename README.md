# E-Commerce Back-End Database

This project is a back-end database for an e-commerce website, built using Node.js, Express.js, and Sequelize as the Object-Relational Mapping (ORM) tool. It provides the necessary database schema and API routes to manage products, categories, and tags for the e-commerce platform.

## Table of Contents

- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Database Configuration](#database-configuration)
- [API Documentation](#api-documentation)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To get started with this project, you can follow the installation steps below and configure the database according to your needs.

## Prerequisites

- Node.js (v14 or higher) installed on your machine.
- MySQL or any other relational database management system.

## Installation

1. Clone this repository to your local machine using:

- git clone https://github.com/your-username/e-commerce-backend.git


2. Change directory to the project folder:


- cd e-commerce-backend


3. Install the required dependencies using npm:


- run 'npm i' to start for installing dependencies



4. Create a `.env` file in the root directory of the project and configure the database connection settings:

DB_NAME=your_database_name
DB_USER=your_database_user
DB_PASSWORD=your_database_password

## Database Configuration

This project uses Sequelize as the ORM tool to interact with the database. The database schema is automatically created and updated based on the models defined in the `models` directory. To create the database and tables, run the following command:

npm run seeds

## API Documentation

The API routes provided by this back-end can be found in the `routes` directory. The following routes are available:

- `/api/products`: CRUD operations for managing products.
- `/api/categories`: CRUD operations for managing categories.
- `/api/tags`: CRUD operations for managing tags.

Please refer to the individual route files for detailed documentation on each endpoint and the expected request/response format.

## Technologies Used

- Node.js
- Express.js
- Sequelize (ORM)
- MySQL (or any other relational database)
- Dotenv (for environment variables)
- Other Node.js modules as listed in `package.json`

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to create a pull request or open an issue in the repository.

## License

This project is licensed under the [MIT License](LICENSE).

## Video Walkthrough
[![Watch the video](https://img.youtube.com/vi/jY24vxxAsX0/hqdefault.jpg)](https://youtu.be/jY24vxxAsX0)
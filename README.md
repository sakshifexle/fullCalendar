# Requirements
- PHP >= 8.0
- Laravel >= 9.x
- Composer
- MySQL or any other supported database
- Node.js and npm (for front-end assets)

# Installation

## Clone the repository:
`git clone https://github.com/sakshifexle/fullCalendar.git`

## Navigate into the project directory:
`cd fullcalendar`

## Install dependencies:
Run Composer to install PHP dependencies:
`composer install`

Run npm to install front-end dependencies (if applicable):
`npm install`
`npm run dev`

Set up environment:

Copy the .env.example file to create your environment settings:
`cp .env.example .env`

Configure your .env file with the correct database and application details:
`DB_DATABASE=your_database`
`DB_USERNAME=your_username`
`DB_PASSWORD=your_password`

Generate application key:
`php artisan key:generate`

## Run migrations:

This will create the necessary tables for the application:
`php artisan migrate`

## Usage

Start the local development server:
`php artisan serve`

Access the application:

Open a browser and go to:

`http://localhost:8000`
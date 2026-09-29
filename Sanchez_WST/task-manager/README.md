# Personal Task Manager

**Project Code: WST21-PM-2026-SF**
**Student Name: Mark Anthony B. Sanchez**
**Course & Year: BSIT-2**
**Database Used: SQLite**

## Features
- Add Task
- View Tasks
- Edit Task
- Delete Task
- Update Status

## Project Overview
This personal task manager is built using Laravel and allows users to create, view, edit, delete, and mark tasks as pending or completed. It follows the required Laravel flow of Routes, Controller, Model, Database, and Blade views.

## Setup
1. Clone the repository.
2. Open the project folder.
3. Install dependencies:
   ```bash
   composer install
   npm install
   ```
4. Run the migrations:
   ```bash
   php artisan migrate
   ```
5. Start the app:
   ```bash
   php artisan serve
   ```
6. Open the browser and visit the local Laravel URL.

## Database
The tasks table includes the following fields:
- id
- task_name
- description
- status
- due_date
- created_at
- updated_at

## Requirements Covered
- Laravel
- Routes
- Controller
- Model
- Blade Views
- Database

## Notes
This project is a simple and functional task manager that focuses on core CRUD operations and task status updates.

## Repository


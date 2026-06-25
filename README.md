## Blood Bank Management System

## Project Overview

A web-based Blood Bank Management System developed using PHP and MySQL. The system helps manage blood donations and blood requests efficiently.

## Features

- Blood donation registration
- Blood request management
- Blood group search
- Admin panel
- Contact page

## Technologies Used

- PHP
- MySQL
- Apache
- Docker
- GitHub

## Project Structure

Blood-Bank-And-Donation-Management-System/
├── admin/
├── image/
├── sql/
├── index.php
├── conn.php
├── Dockerfile
└── README.md

## Docker Setup

### Build Docker Image

```bash
docker build -t blood-bank-app .
```

### Run Container

```bash
docker run -d -p 8080:80 --name blood-bank-container blood-bank-app
```

### Access Application

Open:

http://localhost:8080

## Author

Kshitiz Rohilla
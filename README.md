# GameSwap Platform

## Overview
GameSwap is a web application developed as a collaborative project, designed to provide an organized, modular and scalable platform for managing and displaying game-related content. The system also serves as the foundation for future features such as game trading, user profiles, reviews and marketplace-style extensions.

The project was built with a focus on clean architecture, responsive interface design and simplified deployment through Docker.

---

## Key Objectives
- Provide a modular and scalable structure for managing game catalogs  
- Deliver a clean and responsive user interface using Blade templates  
- Simplify deployment and environment setup with Docker  
- Serve as a reliable foundation for future system expansion  

---

## Technologies Used
- PHP (Blade templating)  
- HTML5 / CSS3  
- JavaScript  
- Node.js (frontend dependencies)  
- Docker  
- Git & GitHub  

---

## Project Structure

GameSwap/
├── public/ # Public files served to the browser
├── src/ # Main application code
├── views/ # Blade templates and UI components
├── Dockerfile # Docker environment configuration
├── package.json # Frontend dependencies
└── README.md # Project documentation


---

## Installation and Usage

### Prerequisites
- Docker installed  
- Git installed  

### Steps

```bash
# Clone the repository
git clone https://github.com/your-username/gameswap-platform.git

# Enter the project folder
cd gameswap-platform

# Build the Docker image
docker build -t gameswap .

# Run the container
docker run -d -p 8080:80 gameswap

Access the application at:

http://localhost:8080

Features

    Modular system for managing game-related content

    Responsive interface built with Blade templates

    Docker-based isolated environment

    Clear and maintainable project structure

    Prepared for future expansion (database integration, trading system, user accounts, etc.)

Team and Contributions

This project was developed collaboratively:

    João Gabriel Santana Nunes – Project Manager / Developer / Module Architect
    Luis Eduardo Nantes Estevam – Assistant Manager / Developer / Module Architect
    Gabriel Gustavo de Oliveira – Developer / Module Architect
    Gonçalo da Silva Martins – Developer / Documentation Specialist

License

A software license (MIT, GPL or other) may be added depending on project requirements.
Repository

https://github.com/your-username/gameswap-platform

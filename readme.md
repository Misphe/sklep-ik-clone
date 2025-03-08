# Sklep-IK.pl Clone

## Description
This project is a clone of the [sklep-ik.pl](https://sklep-ik.pl) e-commerce website, built using PrestaShop 1.7.8. The goal of this project is to replicate the functionality and design of the original website while leveraging modern development tools and technologies.

## Technologies Used
- **PrestaShop:** Version 1.7.8 (e-commerce platform)
- **MySQL:** Version 8.0.33 (database management)
- **phpMyAdmin:** Version 5.2.1 (database administration)
- **Selenium:** Version 4.27.0 (automated testing)
- **Java:** Version 17 (backend and testing)
- **Python:** Version 3.12.0 (scripting and automation)

## Setup and Compilation Instructions

### Prerequisites
- Docker must be installed on your machine.

### Steps to Run the Project
1. **Clone the repository** to your local machine.
2. **Navigate to the project folder.**
3. **Run the Docker Compose command** based on your operating system:

   - **Windows:**
     ```bash
     docker-compose -f shop/docker/local/docker-compose.yml up -d
     ```
   - **macOS/Linux:**
     ```bash
     docker-compose -f shop/docker/local/docker-compose.mac.yml up -d
     ```

4. **Wait for the Docker containers** to initialize.
5. **Open your browser** and navigate to:  
   [https://localhost:19323](https://localhost:19323)

## Project Team
- Mateusz Przyborski
- Jan Kaczerski
- Adrian Belczak

## Notes
- Ensure that port **19323** and any other required ports are free on your machine before running the Docker containers.
- For troubleshooting or additional setup details, refer to the project documentation or contact the team members.

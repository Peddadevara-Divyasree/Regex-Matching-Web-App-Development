# Regex Matching Web Application with Flask

## Overview
This project is a Regex Matching Web Application developed using Python and Flask framework. The application allows users to input a test string and a regular expression (regex) and displays all the matches found. Additionally, it includes a bonus feature to validate email IDs using regex.

## Key Features
- **Regex Matching:** Users can input a test string and a regex pattern to find all matches within the string.
- **Email ID Validation:** Bonus feature to validate email IDs using regex patterns.
- **Deployment on AWS Cloud:** The application is deployed on an AWS EC2 instance, making it accessible over the internet.

## Technologies Used
- Python
- Flask
- HTML
- CSS
- AWS EC2

## Project Structure
- `app.py`: Contains the Flask application code with routes and logic for regex matching and email validation.
- `templates/`: Directory containing HTML templates for the user interface.
  - `index.html`: Template for input form.
  - `results.html`: Template for displaying match results.
- `static/`: Directory for static assets such as CSS files (if any).

## Local Setup
1. Clone the repository to your local machine.
-git clone https://github.com/your_username/regex-web-app.git
2. Navigate to the project directory.
-cd regex-web-app
3. Install Flask and other dependencies.
-pip install Flask
4. Run the Flask application locally.
5. Open a web browser and navigate to `http://localhost:5000` to access the application.

## Deployment on AWS Cloud
To deploy the application on AWS Cloud:
1. Set up an EC2 instance on AWS.
2. Transfer the project files to the EC2 instance.
3. Install necessary dependencies and run the Flask application.
4. Configure security groups and networking settings to allow inbound traffic.
5. Access the application using the public IP address or domain name of the EC2 instance.






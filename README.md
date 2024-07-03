# Playpal--my-final-project
---

# Amateur Athlete Social Network

## Overview
Amateur Athlete Social Network is a web application designed to connect amateur athletes, allowing them to find and match with other athletes based on their preferences and proximity. Users can also create and join events, such as football games, and provide feedback that affects user ratings. The project is built using the Django framework for the backend, with SQLite as the database, and HTML, CSS, and JavaScript for the frontend.

## Features
- **User Registration and Authentication**: Secure user sign-up and login functionalities.
- **User Preferences**: Users can input their details and preferences, which are used to match them with other athletes.
- **Event Management**: Users can create, join, and manage sports events.
- **Feedback System**: Post-event feedback allows users to rate their experiences, affecting the ratings of participants.
- **NLP Analysis**: Natural Language Processing is used to analyze the sentiment of free-text feedback.

## Technologies Used
### Backend
- **Django**: A high-level Python web framework that encourages rapid development and clean, pragmatic design.
- **SQLite**: A lightweight, serverless, and self-contained relational database management system.

### Frontend
- **HTML**: Provides the structure of the web pages.
- **CSS**: Used for styling the web pages to make them visually appealing.
- **JavaScript**: Adds interactivity and dynamic behavior to the web pages.

## Installation
1. **Clone the repository:**

    git clone https://github.com/yourusername/amateur-athlete-social-network.git
    cd amateur-athlete-social-network
  

2. **Create a virtual environment and activate it:**
   
    python3 -m venv venv
    source venv/bin/activate
  

3. **Install the required packages:**

    pip install -r requirements.txt
  

4. **Run migrations:**
  
    python manage.py migrate
 

5. **Run the development server:**
   
    python manage.py runserver
   

6. **Open your web browser and navigate to:**
   
    http://127.0.0.1:8000/
 

## Usage
1. **Register a new user or log in with existing credentials.**
2. **Complete the profile by entering personal details and preferences.**
3. **Explore the dashboard to find and match with other athletes.**
4. **Create or join sports events.**
5. **Provide feedback after events, which will be analyzed for sentiment.**

## Contributing
1. **Fork the repository.**
2. **Create a new branch:**
   
    git checkout -b feature-name
  
3. **Make your changes and commit them:**
   
    git commit -m 'Add feature'
  
4. **Push to the branch:**
 
    git push origin feature-name

5. **Submit a pull request.**


## Contact
If you have any questions or suggestions, feel free to reach out.


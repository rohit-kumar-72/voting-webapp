# Django Voting Web Application

## Overview

This is a simple Django-based web application that allows users to vote on various categories. Users can view available categories, vote for their favorite items in each category, and see the voting results in real-time.


## Features

- User-friendly interface for voting on categories.
- Real-time updates of voting results.
- Secure user authentication and authorization.
- SQLite database for data storage.
- Responsive design for mobile and desktop.
- utilize django forms

## Getting Started

### Prerequisites

- Python (3.6 or higher)
- Django (3.0 or higher)

### Installation

1. Clone this repository to your local machine.

   ```bash
   git clone https://github.com/your-username/voting-app.git
   ```

2. Navigate to the project directory.

   ```bash
   cd voting-app
   ```

3. Create a virtual environment (optional but recommended).

   ```bash
   python -m venv venv
   source venv/bin/activate
   ```

4. Install project dependencies.

   ```bash
   pip install -r requirements.txt
   ```

5. Apply database migrations.

   ```bash
   python manage.py migrate
   ```

6. Create a superuser account to access the Django admin panel.

   ```bash
   python manage.py createsuperuser
   ```

7. Start the development server.

   ```bash
   python manage.py runserver
   ```

8. Open your web browser and access the application at `http://127.0.0.1:8000`.

## Usage

1. Browse the available categories on the homepage.
2. Click on a category to view its items and vote for your favorite.
3. Check real-time voting results on the results page.
4. Use the Django admin panel to manage categories and items.

## Screenshots

1. Signup Page:  New user Create a new Account.

   ![image](https://github.com/user-attachments/assets/9f50d2d0-a639-4ea5-bcde-1b755b9b12ff)

 
 2. Signin Page:  Existing user login here.

    ![image](https://github.com/user-attachments/assets/5c89cb2e-8471-41f1-a9c7-6f2ec856f6d5)


3.  Category Page:  Browse categories and select one to vote.

   ![image](https://github.com/user-attachments/assets/fc23889b-de03-40a7-ac52-daad22f98d4b)


4.  Vote Page:  Vote for your preferred category.

   ![image](https://github.com/user-attachments/assets/18959866-effc-4457-9402-e6dc689c48a6)

5.  Result Page: View the voting results.

   ![image](https://github.com/user-attachments/assets/345c30b1-9c50-4b19-a65b-0c2195905481)


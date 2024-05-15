# Wellness Web: Health Blog Platform

## Objective:
Develop a Django application for a health blog platform where users can read and contribute articles on various health topics.

## Description:

1. **Model Creation:**
   - Define Django models for articles, including fields like title, content, author, etc.
   - Implement models for user registration and authentication.

2. **UI Development:**
   - Develop a user interface for users to browse and read articles.
   - Create views and templates to display articles, authors, and enable users to submit comments.

3. **User Authentication:**
   - Implement user authentication functionality for user registration, login, and logout.
   - Ensure that only authenticated users can submit comments.

4. **Article Submission:**
   - Allow authenticated users to submit new articles.
   - Implement validation to ensure article content meets specified criteria.

## Setup Prerequisites:
Before starting, ensure you have the following installed on your system:
- Python (version 3.6 or higher)
- Django (version 3.0 or higher)

## Installation:
1. Clone the repository to your local machine:
   ```
   git clone https://github.com/tourist1642/Wellness-Web.git
   ```
2. Navigate to the project directory:
   ```
   cd Wellness-Web
   ```
3. Create a virtual environment:
   ```
   virtualenv venv
   ```
4. Activate the virtual environment:
   - On Windows: `venv\Scripts\activate`
   - On macOS and Linux: `source venv/bin/activate`
5. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
6. Perform database migrations:
   ```
   python manage.py migrate
   ```

## Usage:
Run the development server with the following command:
```
python manage.py runserver
```
Once the server is running, access the Wellness Web platform at http://localhost:8000 in your web browser.

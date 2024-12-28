# SubscriptionTracker
A simple web application to manage and get reminders for your subscriptions. This tool helps users keep track of upcoming subscription renewals and sends email notifications to avoid missing deadlines.

# Features
- Add Subscriptions: Easily add subscriptions with details like name, amount, and renewal date.
- View Subscriptions: View all your subscriptions in a table format.
- Email Reminders: Automatically sends email notifications for subscriptions due within 3 days.

# How It Works
- Users can add their subscription details (e.g., Netflix, Amazon Prime).
- The app stores the subscription data in a database.
- It checks for upcoming renewals and sends reminder emails to the registered email address.
 # Screenshots
Home Page
Add Subscription
# Setup Instructions
1. Prerequisites
- Python 3.8 or higher installed.
- Basic knowledge of Python and Flask.
2. Clone the Repository
- git clone https://github.com/your-username/SubscriptionReminder.git
- cd SubscriptionReminder
3. Install Dependencies
- Install the required Python libraries:
- pip install -r requirements.txt
4. Configure Email
- Set up your email credentials in the environment:
- export MAIL_USERNAME=your_email@gmail.com  
- export MAIL_PASSWORD=your_password  
5. Run the App
- Start the Flask application:
- python app.py
6. Access the App
- Open your browser and visit:
- http://127.0.0.1:5000
# Folder Structure
- SubscriptionReminder/
- ├── app.py              # Main application file
- ├── templates/          # HTML templates
- │   ├── index.html      # Home page
- │   ├── add_subscription.html  # Add subscription form
- ├── static/             # Static files (CSS)
- │   ├── styles.css
- ├── requirements.txt    # Dependencies
- ├── README.md           # Project documentation
- └── database.db         # SQLite database (auto-created)

# Future Enhancements

   -  User authentication to manage personal subscriptions.
   -  Support for SMS notifications.
   -  A mobile app version for better accessibility.

# Contributing
- Feel free to fork the repository and submit pull requests. Contributions are welcome!
# License
- This project is licensed under the MIT License

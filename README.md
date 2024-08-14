# Vivaha

## Overview

**Vivaha** is a comprehensive Indian marriage website designed to facilitate matrimonial connections within the Indian community. The platform offers a user-friendly and culturally relevant experience, helping users find compatible life partners through detailed profile creation, advanced search filters, secure messaging, and more.

## Features

- **User Registration and Profile Management:** 
  - Easy registration with detailed profile creation, including personal, educational, and professional details.
  - Option to securely upload and manage photos.

- **Advanced Search Filters:** 
  - Search by criteria such as age, caste, religion, education, profession, location, and more.
  - Save search preferences for quick access to matching profiles.

- **Match Recommendations:**
  - Automated match suggestions based on user preferences and profile information.
  - Ability to shortlist and bookmark favorite profiles.

- **Secure Messaging:**
  - Private and secure messaging system for communicating with potential matches.
  - Real-time notifications with an in-built chat feature.

- **Privacy Controls:**
  - Users can control who can view their profile and photos.
  - Block and report users who violate community guidelines.

- **Profile Verification:**
  - Option for users to verify their profiles, adding credibility and trustworthiness.
  
- **Success Stories:**
  - Dedicated section to share success stories of couples who found their match through Vivaha.

## Installation

To set up the Vivaha website locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/vivaha.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd vivaha
   ```

3. **Set up a virtual environment (optional but recommended):**

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

4. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

5. **Database Setup:**

   Set up your database (e.g., MySQL, PostgreSQL) and configure the database connection in the `settings.py` file.

6. **Run Migrations:**

   ```bash
   python manage.py migrate
   ```

7. **Create a Superuser:**

   ```bash
   python manage.py createsuperuser
   ```

8. **Run the Development Server:**

   ```bash
   python manage.py runserver
   ```

   The website will be accessible at `http://127.0.0.1:8000/`.

## Usage

1. **Registration:**
   - Users can sign up by providing basic details like name, email, and phone number.
   - Complete the profile with additional details such as education, profession, family background, and more.

2. **Searching for Matches:**
   - Use the advanced search filters to find profiles that match your preferences.
   - Browse through recommended profiles based on your criteria.

3. **Messaging and Connecting:**
   - Initiate conversations with potential matches through the secure messaging system.
   - Receive notifications for new messages and profile views.

4. **Privacy Settings:**
   - Adjust privacy settings to control who can view your profile and photos.
   - Use the block and report features to maintain a safe and respectful environment.

## Project Structure

```
vivaha/
├── templates/             # HTML templates for the website
├── static/                # Static files (CSS, JavaScript, images)
├── accounts/              # User accounts management (registration, login, profiles)
├── search/                # Search functionality and filters
├── messaging/             # Messaging system implementation
├── admin/                 # Admin panel for managing the website
├── success_stories/       # Section for success stories
├── settings.py            # Project settings and configurations
├── urls.py                # URL routing
├── manage.py              # Django management script
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```

## Contributing

Contributions to Vivaha are welcome! If you have suggestions for improvements or want to add new features, please feel free to fork the repository and submit a pull request.

---

This README file provides all the necessary information about Vivaha, guiding users through setup, usage, and contributions.

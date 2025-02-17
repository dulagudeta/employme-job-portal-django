```markdown
# Django Job Portal

A comprehensive job portal web application built with Django, designed to connect employers with job seekers. Employers can post job listings, manage applications, while job seekers can search and apply for jobs. The project includes user authentication, dashboard management, and responsive UI using Bootstrap.

## Features

### Employer Features
- **Register/Login**: Create an employer account or log in to an existing one.
- **Post Jobs**: Publish new job listings with details like title, description, and location.
- **Manage Jobs**: Edit or delete existing job postings.
- **View Applications**: Track and review applications submitted by job seekers.

### Job Seeker Features
- **Register/Login**: Create a job seeker account or log in.
- **Search Jobs**: Filter jobs by title, location, or keywords.
- **Apply for Jobs**: Submit applications directly through the portal.
- **Profile Management**: Update personal details, resume, and skills.

### General Features
- **User Authentication**: Secure registration, login, and password reset functionality.
- **Responsive Design**: Mobile-friendly UI built with Bootstrap.
- **Dashboard**: Personalized dashboard for both employers and job seekers.
- **Admin Panel**: Django admin interface for managing users, jobs, and applications.

## Technologies Used
- **Backend**: Django 4.x
- **Frontend**: HTML, CSS, Bootstrap 5
- **Database**: SQLite (default; can be configured for PostgreSQL/MySQL)
- **Dependencies**: 
  - `django-crispy-forms` for form styling
  - `pillow` for image handling
  - `python-dotenv` for environment variables

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/django-job-portal.git
   cd django-job-portal
   ```

2. **Set Up a Virtual Environment** (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run Migrations**:
   ```bash
   python manage.py migrate
   ```

5. **Create a Superuser** (for admin access):
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the Development Server**:
   ```bash
   python manage.py runserver
   ```

Visit `http://localhost:8000` to access the application.

## Configuration

1. **Environment Variables**:
   - Create a `.env` file in the project root.
   - Add the following variables:
     ```
     SECRET_KEY=your_django_secret_key
     DEBUG=True  # Set to False in production
     EMAIL_HOST_USER=your_email@example.com
     EMAIL_HOST_PASSWORD=your_email_password
     ```

2. **Database** (Optional):
   - Modify `settings.py` to use PostgreSQL/MySQL instead of SQLite.

3. **Email Setup** (for password resets):
   - Configure email backend settings in `settings.py`.

## Usage

1. **Access the Application**:
   - Navigate to `http://localhost:8000`.
   - Register as an employer or job seeker.

2. **Admin Dashboard**:
   - Visit `http://localhost:8000/admin` and log in with the superuser account.

3. **Post a Job** (Employers):
   - Log in, go to the dashboard, and click "Post a Job".

4. **Apply for a Job** (Job Seekers):
   - Log in, search for jobs, and click "Apply Now".

## Contributing

Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/your-feature`.
3. Commit changes: `git commit -m 'Add your feature'`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Open a Pull Request.

Ensure your code adheres to PEP8 standards and includes relevant tests.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Contact

For questions or feedback, reach out at [dulagudeta22@gmail.com](mailto:dulagudeta22@gmail.com).
```

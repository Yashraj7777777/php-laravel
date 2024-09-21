User Detail Management CRUD Application
Description
This Laravel-based User Detail Management application enables administrators to efficiently manage user records through full CRUD (Create, Read, Update, Delete) functionality. The application includes features for adding, editing, viewing, and deleting user details, ensuring data integrity and user-friendly interactions.

Key Features
User Form: Collects essential user details (Name, Email, Mobile, Address, Profile Image).
Validation: Enforces data integrity with strict validation rules for input fields.
Database Operations:
Insert user data into the database.
View user records in a structured table format.
Edit and delete user records.
Admin Panel: User-friendly interface for managing user records with options to view full details and profile images.
Bonus Enhancements
Pagination: Efficient handling of large datasets in user lists.
Search Functionality: Quick user lookup by name or email.
Flash Messages: Notifications for successful or failed operations.
Client-Side Validation: Improved user experience with instant feedback.
Image Preview: Allows users to preview their uploaded profile image before submission.
Installation
Clone the repository: git clone [repository_url]
Navigate to the project directory: cd user-detail-management
Install dependencies: composer install
Set up the environment file: cp .env.example .env
Generate application key: php artisan key:generate
Run migrations: php artisan migrate
Serve the application: php artisan serve
For detailed setup instructions and usage, please refer to the documentation in the repository.

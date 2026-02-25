# PSUSphere

### Project Description
PSUSphere is a Django-based web application designed to manage student organizations, college departments, and academic programs. It provides an administrative interface to track student memberships within various organizations and maintains a record of college-specific data.

### Key Features
* **College Management**: Track different college departments with automated timestamps for record creation and updates.
* **Program Tracking**: Manage academic programs and link them directly to their respective colleges.
* **Organization Records**: Maintain a database of student organizations, including detailed descriptions and college affiliations.
* **Student Membership**: Register students and manage their memberships in specific organizations, including the date they joined.
* **Advanced Admin Interface**: Custom search fields and filters in the Django Admin for efficient data management.
* **Automated Data Seeding**: Includes a management command to generate initial fake data for testing using the Faker library.

### Authors
* [Marco Dela Serna]
* [Ace Camias]
fseqweqwe
### Setup and Installation
1.  **Activate Virtual Environment**:
    * Windows: `psusenv\Scripts\activate`
    * Linux/macOS: `source bin/activate`
2.  **Install Dependencies**: `pip install -r requirements.txt`
3.  **Apply Migrations**: `python manage.py migrate`
4.  **Run Server**: `python manage.py runserver`

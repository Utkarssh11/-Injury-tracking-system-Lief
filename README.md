# Injury Tracking System

The Injury Tracking System is a web application designed for organizations, such as the police, to efficiently record and manage injury reports submitted by individuals. This application offers a range of features to streamline injury reporting, management, and user authentication, while providing a clean and user-friendly interface for an enhanced user experience.

## Features

### Report Management

- **Create, View, Update, and Delete Reports**: Users can easily create, view, update, and delete injury reports, allowing for efficient management of reported injuries.

- **Injury Report Information**: Each injury report includes the following details:
  - Name of the reporter
  - Date and time of the injury

### Body Map Annotation

- **Body Map Image Annotation**: Users can pinpoint and label different areas of injury on a body map image. For instance, if a user encircles the left hand and left foot, the system automatically labels these areas as "1" and "2" respectively.

- **Injury Details**: For each encircled area, users can provide detailed information about the injuries. This information is organized in labeled boxes, corresponding to the numbered areas on the body map.

### List of Reports

- **Comprehensive Report List**: Users can access a list or table displaying all reported injuries. This list includes essential information for each report:
  - Name of the reporter
  - Date and time of the injury
  - Date of the report

- **Sorting**: Users can sort the list by any of the fields mentioned above to quickly find and categorize reports.

- **Search by Name**: The search functionality allows users to locate specific reports by the name of the reporter.

- **Filtering**: Users can filter reports based on the start and end dates of the injury and the date and time of the report.

### User Authentication

- **User Registration**: Users can register for an account within the application using a username and password. Additionally, options for Google login and email login are available to provide flexibility in authentication methods.

- **Authentication via Auth0**: User authentication is implemented using Auth0, a secure identity management platform that ensures user data privacy.

- **Account Management**: Registered users can log in and out of their accounts and access a history of their tasks, creating a seamless and personalized experience.

### UI/UX

- **Clean and User-Friendly Interface**: The application features a clean and user-friendly interface designed using Next.js with the Ant Design library. The interface prioritizes usability and ease of navigation.

- **Responsive Design**: The application is optimized for both desktop and mobile devices, providing a consistent and enjoyable user experience across various platforms.

- **Visually Appealing**: The user interface is visually appealing, enhancing the overall user experience and making the application more inviting and intuitive.

### Technologies Used

#### Front-end:
- **Framework**: Next.js
- **UI Library**: Ant Design

#### Back-end:
- **ORM (Object-Relational Mapping)**: Prisma
- **Database**: PostgreSQL

#### Authentication:
- **Authentication Provider**: Auth0
- **Login Options**: Google login, email login

#### Progressive Web App (PWA):
- **Service Workers and PWA Features**: Implemented for enhanced performance and offline capabilities.

## Usage

To use the Injury Tracking System, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine using `git clone`.

2. **Set Up the Application**: Follow the provided setup instructions to configure the application and database.

3. **Register and Log In**: Create an account or use existing credentials to log in to the application.

4. **Report and Manage Injuries**: Create, view, update, and delete injury reports, pinpoint injuries on the body map, and provide injury details.

5. **Explore the List of Reports**: Access the comprehensive list of injury reports, sort, search, and filter as needed.

6. **Log Out**: Log out of your account when done, ensuring the security and privacy of your data.


---


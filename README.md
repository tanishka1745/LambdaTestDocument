# LambdaTestDocument
# Configuration Management System for KaneAI & Test Manager

## Introduction
The Configuration Management system within KaneAI aims to streamline the process of managing, allocating, and maintaining configurations for various test cases and test runs. This system is designed to ensure that QA Engineers and Development Managers can efficiently handle configurations, leading to more effective and accurate testing processes.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [User Roles](#user-roles)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features
- **Configuration Types:**
  - Desktop
  - Real Device (Public Cloud & Private Cloud)
  - Virtual Device
- **Configuration Parameters:**
  - OS, OS Version, Browser, Browser Version, Device Name, Application, Resolution
- **Regular Expression Structure:**
  - For selecting Manufacturer, Device Name, and OS Version for real devices
- **Allocation System:**
  - Allocate configurations to test cases and test runs
- **Application Maintenance:**
  - Update and edit application versions within configurations
- **User Permissions and Roles:**
  - Define user roles and permissions for managing configurations

## Installation
To install and set up the Configuration Management system, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/configuration-management-system.git
   ```

2. Navigate to the project directory:
   ```sh
   cd configuration-management-system
   ```

3. Install dependencies:
   ```sh
   npm install
   ```

4. Set up the database:
   ```sh
   npm run setup-db
   ```

5. Start the development server:
   ```sh
   npm start
   ```

## Usage
Once the system is installed, you can start managing configurations using the user interface. Here are some key actions you can perform:

- **Add New Configuration:** Click the "Add New Configuration" button and fill in the required parameters.
- **Edit Configuration:** Click the "Edit" button next to a configuration to modify its parameters.
- **Allocate Configuration:** Assign configurations to test cases and test runs.
- **Update Application:** Edit application versions within configurations.
- **Manage Users:** Define and manage user roles and permissions.

## User Roles
The system supports the following user roles:

- **Admin:** Can add, edit, and delete configurations, and manage users.
- **QA Engineer:** Can add and edit configurations, and allocate configurations to test cases.
- **Development Manager:** Can view and edit configurations, and generate reports.

## Contributing
We welcome contributions to improve the Configuration Management system. To contribute:

1. Fork the repository.
2. Create a new branch:
   ```sh
   git checkout -b feature-branch
   ```
3. Make your changes and commit them:
   ```sh
   git commit -m "Add new feature"
   ```
4. Push to the branch:
   ```sh
   git push origin feature-branch
   ```
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact
For any questions or suggestions, please contact:
- Name: Tanishka
- Email: tanishka1745@example.com

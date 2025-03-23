# Wireframes for Configuration Management System

## Configuration Management Interface

### Wireframe 1: List of Existing Configurations

```
+---------------------------------------------------+
| Configuration Management                          |
+---------------------------------------------------+
| + Add New Configuration                           |
+---------------------------------------------------+
| Filter: [OS] [Device] [App]                       |
+---------------------------------------------------+
| Configurations List                               |
|---------------------------------------------------|
| [Edit] Desktop - Windows 10 - Chrome 89           |
| [Edit] Real Device - Android - Samsung S21        |
| [Edit] Virtual Device - iOS - iPhone 12           |
| [Edit] Real Device - iOS - Private Cloud          |
| [Edit] Real Device - iOS - Public Cloud           |
| ...                                               |
+---------------------------------------------------+
| [Duplicate] [Delete]                              |
+---------------------------------------------------+
```
**Description:**
- **Add New Configuration:** Button to add a new configuration.
- **Filter:** Dropdown filters for OS, Device, and App to quickly find specific configurations.
- **Configurations List:** Displays existing configurations with options to edit, duplicate, and delete.

### Wireframe 2: Add New Configuration

```
+---------------------------------------------------+
| Add New Configuration                             |
+---------------------------------------------------+
| Type: [Desktop] [Real Device] [Virtual Device]    |
+---------------------------------------------------+
| Parameters:                                       |
|   OS: [Dropdown]                                  |
|   OS Version: [Dropdown]                          |
|   Browser: [Dropdown]                             |
|   Browser Version: [Dropdown]                     |
|   Device Name: [Text Field]                       |
|   Application: [Text Field]                       |
|   Resolution: [Text Field]                        |
+---------------------------------------------------+
| [Save] [Cancel]                                   |
+---------------------------------------------------+
```
**Description:**
- **Type:** Radio buttons to select the type of configuration (Desktop, Real Device, Virtual Device).
- **Parameters:** Fields for entering configuration parameters.
- **Save/Cancel:** Buttons to save the new configuration or cancel the action.

### Wireframe 3: Edit Configuration

```
+---------------------------------------------------+
| Edit Configuration                                |
+---------------------------------------------------+
| Type: [Desktop]                                   |
+---------------------------------------------------+
| Parameters:                                       |
|   OS: Windows 10                                  |
|   OS Version: 20H2                                |
|   Browser: Chrome                                 |
|   Browser Version: 89                             |
|   Resolution: 1920x1080                           |
+---------------------------------------------------+
| [Save] [Cancel]                                   |
+---------------------------------------------------+
```
**Description:**
- **Type:** Display the type of configuration being edited.
- **Parameters:** Editable fields for configuration parameters.
- **Save/Cancel:** Buttons to save changes or cancel the action.

### Wireframe 4: Configuration Details

```
+---------------------------------------------------+
| Configuration Details                             |
+---------------------------------------------------+
| Type: [Desktop]                                   |
+---------------------------------------------------+
| Parameters:                                       |
|   OS: Windows 10                                  |
|   OS Version: 20H2                                |
|   Browser: Chrome                                 |
|   Browser Version: 89                             |
|   Resolution: 1920x1080                           |
+---------------------------------------------------+
| Allocation Status:                                |
|   Test Cases: [List of Test Cases]                |
|   Test Runs: [List of Test Runs]                  |
+---------------------------------------------------+
| History:                                          |
|   [Timestamp] Configuration created               |
|   [Timestamp] OS Version updated to 20H2          |
|   ...                                             |
+---------------------------------------------------+
| [Edit] [Duplicate] [Delete]                       |
+---------------------------------------------------+
```
**Description:**
- **Type:** Display the type of configuration.
- **Parameters:** Display the configuration parameters.
- **Allocation Status:** List of test cases and test runs allocated to this configuration.
- **History:** Log of changes made to the configuration.
- **Edit/Duplicate/Delete:** Buttons for editing, duplicating, or deleting the configuration.

## Application Management Interface

### Wireframe 5: Application Management

```
+---------------------------------------------------+
| Application Management                            |
+---------------------------------------------------+
| Applications List                                 |
|---------------------------------------------------|
| [Edit] App1 - Version 1.2                         |
| [Edit] App2 - Version 2.1                         |
| [Edit] App3 - Version 3.0                         |
| ...                                               |
+---------------------------------------------------+
| + Add New Application                             |
+---------------------------------------------------+
```
**Description:**
- **Applications List:** Displays existing applications with options to edit.
- **Add New Application:** Button to add a new application.

### Wireframe 6: Add/Edit Application

```
+---------------------------------------------------+
| Add/Edit Application                              |
+---------------------------------------------------+
| Application Name: [Text Field]                    |
| Version: [Text Field]                             |
+---------------------------------------------------+
| [Save] [Cancel]                                   |
+---------------------------------------------------+
```
**Description:**
- **Application Name:** Text field for entering the application name.
- **Version:** Text field for entering the application version.
- **Save/Cancel:** Buttons to save changes or cancel the action.

## User Management Interface

### Wireframe 7: User Management

```
+---------------------------------------------------+
| User Management                                   |
+---------------------------------------------------+
| Users List                                        |
|---------------------------------------------------|
| [Admin] John Doe                                  |
| [QA Engineer] Jane Smith                          |
| [Dev Manager] Emily Johnson                       |
| ...                                               |
+---------------------------------------------------+
| + Add New User                                    |
+---------------------------------------------------+
| [Edit] [Delete]                                   |
+---------------------------------------------------+
```
**Description:**
- **Users List:** Displays existing users with their roles.
- **Add New User:** Button to add a new user.
- **Edit/Delete:** Buttons for editing or deleting a user.

### Wireframe 8: Add/Edit User

```
+---------------------------------------------------+
| Add/Edit User                                     |
+---------------------------------------------------+
| Username: [Text Field]                            |
| Role: [Dropdown: Admin, QA Engineer, Dev Manager] |
+---------------------------------------------------+
| [Save] [Cancel]                                   |
+---------------------------------------------------+
```
**Description:**
- **Username:** Text field for entering the username.
- **Role:** Dropdown to select the user role.
- **Save/Cancel:** Buttons to save changes or cancel the action.

### Wireframe 9: Role-Based Access Control

```
+---------------------------------------------------+
| Role-Based Access Control                         |
+---------------------------------------------------+
| Roles List                                        |
|---------------------------------------------------|
| [Admin]                                           |
|   - Can add/edit/delete configurations            |
|   - Can manage users                              |
| [QA Engineer]                                     |
|   - Can add/edit configurations                   |
|   - Can allocate configurations to test cases     |
| [Dev Manager]                                     |
|   - Can view and edit configurations              |
|   - Can generate reports                          |
| ...                                               |
+---------------------------------------------------+
| + Add New Role                                    |
+---------------------------------------------------+
| [Edit] [Delete]                                   |
+---------------------------------------------------+
```
**Description:**
- **Roles List:** Displays existing roles with their permissions.
- **Add New Role:** Button to add a new role.
- **Edit/Delete:** Buttons for editing or deleting a role.

### Wireframe 10: Add/Edit Role

```
+---------------------------------------------------+
| Add/Edit Role                                     |
+---------------------------------------------------+
| Role Name: [Text Field]                           |
| Permissions:                                      |
|   [Checkbox] Can add/edit/delete configurations   |
|   [Checkbox] Can manage users                     |
|   [Checkbox] Can allocate configurations          |
|   [Checkbox] Can generate reports                 |
|   ...                                             |
+---------------------------------------------------+
| [Save] [Cancel]                                   |
+---------------------------------------------------+
```
**Description:**
- **Role Name:** Text field for entering the role name.
- **Permissions:** Checkboxes for assigning permissions to the role.
- **Save/Cancel:** Buttons to save changes or cancel the action.

# ATM and Banking Management System

This C++ project provides a simple command-line ATM and banking management system. It allows users to perform various banking operations such as creating accounts, viewing account details, depositing and withdrawing money, and viewing transaction history. The system also supports basic user management for admins to handle client information and permissions.

## Features

### ATM System
- **Deposit Money**: Add funds to a user’s account.
- **Withdraw Money**: Withdraw funds from a user’s account with checks to ensure sufficient balance.
- **Check Balance**: View the current balance of the user’s account.
- **Transaction History**: View a history of recent transactions.

### Banking Management System
- **Add New Client**: Allows admin users to add new clients to the system.
- **Delete Client**: Remove a client’s account from the system.
- **Update Client Information**: Modify details such as name, address, and phone number for a client.
- **Find Client**: Search for and view a client’s details by account number.
- **View All Clients**: Display a list of all registered clients.
- **User Management**: Allows admin users to manage other users by adding, updating, deleting, or finding user accounts.

### Access Control
- User permissions are defined for different operations. Only authorized users can access certain functionalities, such as client and user management.

## Code Structure

### Main Components

- **ATM Functions**:
  - `ShowATMMenue()`: Displays ATM operations and options for users.
  - **Deposit**: Accepts an amount and adds it to the user’s balance.
  - **Withdraw**: Accepts an amount to withdraw from the balance, with balance validation.
  - **Check Balance**: Displays the current balance.
  - **Transaction History**: Shows a log of recent transactions for the user.

- **Banking Management Functions**:
  - `ShowBankManagementMenue()`: Displays banking management operations for admins.
  - **Add New Client**: Admins can register new clients with relevant information.
  - **Delete Client**: Removes a client account by account number.
  - **Update Client**: Edits details for a specified client.
  - **Find Client**: Searches and displays a client’s details.
  - **View All Clients**: Lists all client accounts and basic details.

- **User Management**:
  - `ShowUserManagementMenue()`: Displays options for managing user accounts.
  - **Add User**: Allows creation of a new user account.
  - **Delete User**: Removes a user from the system by username.
  - **Update User**: Edits an existing user’s details.
  - **Find User**: Searches for a user and displays their information.

#### File Structure
- **Client Data (clients.txt)**:
- **User Data (users.txt)**:
  
All Data Save in 2 Files


1. **Login**: Users log in with a username and password.
2. **Navigation**: Based on the user’s role and permissions, they can access ATM features, client management, or user management.
3. **Permissions Check**: Admin-only features are restricted to authorized users.
4. **Perform Operations**: Users can carry out transactions, manage client and user data, and view their transaction history.
5. **Logout**: Users can choose to log out, returning to the login screen.


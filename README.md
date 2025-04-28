# Blood-Bank-Project

## Description

The Blood Bank Management System is a project designed to simplify the management of blood donations, inventory tracking, and donor/recipient information. This system streamlines the processes for blood banks, hospitals, and donors, ensuring efficient and accurate data recording and retrieval.

## Features

- **Donor Management:** Add, update, and manage donor details.
- **Recipient Management:** Track requests and manage recipient information.
- **Blood Inventory:** Maintain records of available blood types and their quantities.
- **Matching System:** Find compatible blood types for recipients.
- **Notifications:** Notify donors about donation events and blood requirements.
- **Reports:** Generate reports for inventory, donors, and recipients.

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript,React,Redux.
- **Backend:** Node.js, Express.js. 
- **Database:** MySQL
- **Other Tools:** Docker, GitHub Actions, etc.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ritesh2320/blood-bank.git
   cd blood-bank
   ```

2. Install dependencies:
   in both api and client 
   ```bash
   npm install
   ```

4. Set up the environment variables in a `.env` file:
   ```
   DB_HOST=your_database_host
   DB_USER=your_database_user
   DB_PASSWORD=your_database_password
   ```

5. Run the application:
   for client:
   ```bash
   npm start
   ```
   for api:
   ```bash
   npm run dev
   ```

## Usage

- Open the application in your browser at `http://localhost:5173`.
- Log in or sign up as an administrator, donor, or recipient.
- Use the dashboard to manage blood donations, inventory, and requests.

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add a new feature"
   ```
4. Push your changes:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## Contact

For questions or suggestions, please contact [ritesh2320](https://github.com/ritesh2320).

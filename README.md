# Proactively - Speaker Booking Platform

## Overview

Proactively is a web application designed to facilitate the booking of speakers for speaker sessions. The platform offers a simple, user-friendly interface to manage bookings efficiently. This project was developed as part of the Proactively internship application backend assignment.

---

## Features

- **Book Speakers:** A seamless interface to book speakers for various sessions.
- **Modular Code Structure:** Implemented using the MVC (Model-View-Controller) pattern for modularity and maintainability.
- **GUI Support:** A simple front-end GUI built with React TypeScript for interacting with the backend.
- **Postman Integration:** Backend APIs are fully documented and tested using Postman collections.
- **Email Notifications:** Upon session confirmation, an email notification is sent to both parties, stating the session date and timings.
- **Google Calendar Integration:** Sessions are tracked onto both parties' Google Calendars when confirmed.

---

## Technology Stack

- **Frontend:** React TypeScript
- **Backend:** Node.js, Express.js
- **Database:** MySQL

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/eden-max-stack/Proactively
   ```

2. Navigate to the backend directory:

   ```bash
   cd proactivelyBackend
   ```

3. Install backend dependencies:

   ```bash
   npm install
   ```

4. Install frontend dependencies:

   ```bash
   npm install
   ```

5. Set up the database:

   - Ensure MySQL is installed and running.
   - Create a database and configure connection details in the backend.

6. Start the application:
   - Backend:
     ```bash
     node server.js
     ```
   - Frontend:
     ```bash
     npm run dev
     ```

---

## API Documentation

API endpoints are tracked and documented using Postman. You can find the Postman collection in the file named `Proactively.postman_collection.json` located outside the backend directory.

---

## Known Issues

- **Refresh Token Generation:** There are issues with refresh tokens not being generated properly.
- **GUI Bugs:** Some minor graphical user interface issues need resolution.

---

## Future Improvements

- Fix refresh token generation logic.
- Enhance GUI for better user experience.

---

## Contributing

Feel free to fork the repository and submit pull requests for bug fixes or feature enhancements.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgements

This project was developed as part of the Proactively internship application backend assignment.

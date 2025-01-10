# LINKLY

LINKLY is a URL Shortener system that simplifies long URLs into short, manageable links. It offers additional features like custom alias options, an analytics dashboard, and a user-friendly interface to track and manage shortened links efficiently.

## Features

- **URL Shortening:** Convert long URLs into short, easy-to-share links.
- **Custom Aliases:** Allow users to create personalized aliases for their shortened URLs.
- **Analytics Dashboard:** Track click statistics and usage metrics for each shortened link.
- **Searchable Dashboard:** Manage and search for your shortened links quickly and efficiently.
- **Responsive Design:** Ensures a seamless experience on both desktop and mobile devices.

## Technologies Used

### Frontend:
- **React.js:** For building an interactive and responsive user interface.
- **JavaScript:** For dynamic functionality and real-time updates.
- **HTML, CSS:** For structuring and styling the application.

### Backend:
- **Node.js & Express.js:** For developing a robust and scalable server-side application.

### Database:
- **MongoDB:** For storing URLs, aliases, and click data securely.

## Setup and Installation

### Prerequisites:
- Node.js installed on your system.
- MongoDB database set up and running.

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/DeepakGaut/LINKLY.git
   ```
2. Navigate to the project directory:
   ```bash
   cd LINKLY
   ```
3. Install dependencies for the frontend:
   ```bash
   cd frontend
   npm install
   ```
4. Install dependencies for the backend:
   ```bash
   cd ../backend
   npm install
   ```
5. Configure environment variables:
   - Create a `.env` file in the `backend` directory and add your MongoDB connection string and other necessary variables.

6. Start the application:
   - Start the backend:
     ```bash
     npm start
     ```
   - Start the frontend:
     ```bash
     cd ../frontend
     npm start
     ```

### Accessing the App:
- Open your browser and go to `http://localhost:3000` to access the application.

## Project Structure
```
LINKLY
├── frontend
│   ├── public
│   └── src
│       ├── components
│       ├── pages
│       └── styles
├── backend
│   ├── models
│   ├── routes
│   ├── controllers
│   └── utils
└── README.md
```

## Contribution
Contributions are welcome! If you'd like to contribute, please fork the repository and create a pull request with your proposed changes.

## Contact
For any inquiries, please reach out to **Deepak Gautam** at [imdeepakgautam@gmail.com](mailto:imdeepakgautam@gmail.com).

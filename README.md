# Tubonge

**Tubonge** is a cutting-edge real-time chat application developed using React Native Expo, Python Django, Socket.io, Firebase, and PostgreSQL. The application features real-time messaging, video and voice call functionalities, and phone number-based authentication, all while being styled with React Native Paper to ensure a modern and user-friendly interface.

## Features

- **Real-Time Messaging**: Engage in dynamic, real-time conversations with support for emojis.
- **Video and Voice Calls**: Connect with friends and colleagues through high-quality video and voice call functionalities.
- **Phone Number Authentication**: Secure and streamlined authentication using Firebase’s phone number-based login.
- **Modern User Interface**: An aesthetically pleasing and intuitive UI designed with React Native Paper.

## Technologies Used

### Frontend
- **React Native Expo**: Framework for building native mobile applications using JavaScript and React.
- **React Native Paper**: UI library for building Material Design compliant components.
- **Firebase**: Authentication service for handling user login and registration.
- **Socket.io**: Library for enabling real-time communication and chat functionality.

### Backend
- **Python Django**: Web framework for building robust and scalable RESTful APIs.
- **Django Channels**: Extension to handle WebSocket connections for real-time features.
- **PostgreSQL**: Relational database system for storing user and message data.

### Deployment
- **Render.com**: Hosting service for deploying the Django backend.
- **Expo Application Services (EAS)**: Service for building and deploying the APK for Android.

## Getting Started

To set up and run the Tubonge project locally, follow the instructions below:

### Prerequisites

- **Node.js** (for frontend development)
- **Python** (for backend development)
- **PostgreSQL** (for the database)
- **Expo CLI** (for running the React Native app)

### Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Bria222/Tubonge-Chat-App-Development.git
   cd Tubonge
   ```

2. **Frontend Setup**
   - Navigate to the frontend directory:
     ```bash
     cd frontend
     ```
   - Install dependencies:
     ```bash
     npm install
     ```
   - Configure Firebase and other environment variables by creating a `.env` file in the `frontend` directory with appropriate values.

3. **Backend Setup**
   - Navigate to the backend directory:
     ```bash
     cd backend
     ```
   - Install dependencies:
     ```bash
     pip install -r requirements.txt
     ```
   - Set up PostgreSQL and configure Django settings in `backend/tubonge_backend/settings.py`.

4. **Run the Application**
   - **Frontend**:
     ```bash
     expo start
     ```
   - **Backend**:
     ```bash
     python manage.py migrate
     python manage.py runserver
     ```

## Usage

- **Frontend**: Launch the app using Expo CLI and follow the on-screen instructions to register and log in.
- **Backend**: Ensure the Django server is running and accessible. It will handle API requests and WebSocket connections.

## Contributing

We welcome contributions from the community! If you have suggestions, improvements, or bug fixes, please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`.
3. Commit your changes: `git commit -am 'Add new feature'`.
4. Push the branch: `git push origin feature/your-feature`.
5. Create a pull request detailing your changes.

## License

This project is licensed under the [MIT License](LICENSE). See the LICENSE file for details.

## Acknowledgments

- **React Native** and **React Native Paper** for providing a solid foundation for mobile app development.
- **Firebase** for enabling easy authentication and real-time database capabilities.
- **Django** and **Django Channels** for robust backend support.

For any questions or support, feel free to open an issue in the GitHub repository.

---

**Tubonge** is developed and maintained by Brian. Thank you for checking out our project!

```

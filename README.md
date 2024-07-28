# Project Manager App

**Project Manager App** is an intuitive project management tool built with Android Studio using Kotlin. It leverages advanced Android features and integrates seamlessly with Firebase to provide a simple yet robust platform for managing projects, tasks, and team collaboration.

## Features

- **Project and Task Management**: Create, manage, and track projects and tasks effortlessly.
- **Board and Card System**: Organize projects using boards and cards, assigning tasks to team members.
- **User Assignment**: Assign tasks to specific team members and keep everyone informed.
- **Real-time Notifications**: Get notified of assigned tasks and updates instantly through Firebase Cloud Messaging (FCM).
- **Customizable Cards**: Rearrange, color, delete, and update cards to suit your workflow.

## Technologies Used

- **Kotlin**: The app is developed using Kotlin, ensuring modern, concise, and safe code.
  - **RecyclerView**: Efficiently display large sets of data within a scrolling view.
  - **DrawerLayout**: Navigate through different sections of the app with ease.
  - **Intents**: Communicate between different components of the app seamlessly.
- **Firebase**:
  - **Firestore**: Store and sync data in real-time across all users.
  - **Auth**: Handle user authentication securely.
  - **Cloud Messaging**: Send notifications to users about updates and assignments.

## Getting Started

To get a local copy up and running, follow these simple steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/your-username/Project-Manager-App.git
    ```

2. **Open the project in Android Studio**:
    - File -> Open -> Navigate to the cloned repository

3. **Add your Firebase configuration**:
    - Follow the Firebase setup instructions to add your `google-services.json` file.

4. **Build and run the project**:
    - Click the "Run" button in Android Studio or use `Shift + F10`.

## Usage

1. **Create a Project**:
    - Click on the "New Project" button and fill in the project details.
2. **Manage Boards and Cards**:
    - Within a project, create boards and add cards to manage tasks.
3. **Assign Tasks**:
    - Assign tasks to team members by selecting a card and assigning a user.
4. **Receive Notifications**:
    - Users will receive notifications for tasks assigned to them and updates.

## Contribution

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. **Fork the Project**
2. **Create your Feature Branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your Changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the Branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

## License

Distributed under the MIT License. See `LICENSE` for more information.


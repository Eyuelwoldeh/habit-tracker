# Habit Tracker

Habit Tracker is a simple and interactive web application built with React, designed to help you create, track, and maintain your daily habits. Whether you're working on personal growth, fitness goals, or productivity, this app allows you to monitor your progress and stay motivated. The app uses localStorage to save your data, ensuring it persists even after you close and reopen the app.

## Features

- **Add New Habits**: Easily add new habits with a name to start tracking them.
- **Track Habit Completion**: Mark a habit as completed for the day and track how many days you've successfully completed it.
- **Delete Habits**: Remove any habit you no longer wish to track.
- **Persistent Data**: Your habit data is stored locally using the browser's localStorage API, so it remains intact between sessions and page reloads.
- **Responsive Design**: The app is built to work on both desktop and mobile devices, making it accessible anywhere, anytime.

## Technologies Used

- **React**: A JavaScript library for building user interfaces. It's perfect for creating dynamic and responsive web apps like this one.
- **localStorage**: A web storage solution that allows data to persist in the browser even after a page refresh. It helps store habit data locally so users don't lose their progress.
- **CSS**: Custom styling for making the app visually appealing and user-friendly.

## Installation

To get this project running locally on your machine, follow the steps below:

### Clone the repository

First, clone the repository to your local machine using Git:

```bash
git clone https://github.com/your-username/habit-tracker.git
cd habit-tracker
```
## Install dependencies
Once the project is cloned, install all the necessary dependencies by running the following command:

```bash
npm install
```

## Start the app
After the dependencies are installed, you can start the development server and open the app in your browser:

```bash
npm start
```

The app will be available at http://localhost:3000 in your browser.

## Usage

Once the app is running, you can:

- **Add a new habit**: Enter a habit name in the input field and click "Add Habit" to create a new habit.
- **Increment completed days**: Click the "Increment" button next to a habit to increase the number of completed days.
- **Delete a habit**: If you no longer want to track a habit, click the "Delete" button (trash icon) next to the habit name.
- **View progress**: The app will show the number of completed days for each habit, helping you visualize your progress.

## Data Persistence

All your habits and progress are saved in the browser's localStorage. This means that even if you refresh the page or close and reopen the app, your data will remain intact.

## Contributing

Contributions are always welcome! If you find a bug or have an idea for a new feature, feel free to fork the repository, create a new branch, and submit a pull request. Here’s how you can contribute:

1. Fork the repo
2. Create a new branch (git checkout -b feature-xyz)
3. Commit your changes (git commit -am 'Add new feature xyz')
4. Push to the branch (git push origin feature-xyz)
5. Open a pull request

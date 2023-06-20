# Realtime Shopping List App

This is a simple web application that allows users to create and manage a realtime shopping list. The app is built using JavaScript and Firebase Realtime Database.

## Features

- Add items to the shopping list in realtime.
- Remove items from the shopping list by clicking on them.
- Updates are synchronized in realtime across all connected devices.

## Prerequisites

Before running the application, make sure you have the following:

- A modern web browser.
- An active internet connection.

## Getting Started

To get started with the app, follow these steps:

1. Clone the repository or download the files to your local machine.
2. Open the `index.html` file in your preferred web browser.

## Usage

1. Enter an item in the input field.
2. Click the "Add" button to add the item to the shopping list.
3. To remove an item from the shopping list, click on it.
4. The shopping list will be updated in realtime across all connected devices.

## Configuration

The Firebase SDK is used to connect to the Realtime Database. The configuration is already set up in the `appSettings` object in the JavaScript code. However, if you want to use your own Firebase project, follow these steps:

1. Go to the [Firebase Console](https://console.firebase.google.com/) and create a new project.
2. In the project settings, find the Firebase SDK configuration and copy the `apiKey`, `authDomain`, `projectId`, and `databaseURL` values.
3. Replace the `appSettings` object in the JavaScript code with your own configuration values.

```javascript
const appSettings = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  databaseURL: "YOUR_DATABASE_URL",
};
```

4. Save the changes and reload the application.

## Contributing

Contributions are welcome! If you have any improvements or bug fixes, feel free to submit a pull request.

## Author

- Emmanuel Chukwu

## License

This project is licensed under the [MIT License](LICENSE).
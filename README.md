Sure, here is the updated README with the link to the web app version of Pastry Paradise:

---

# Pastry Paradise

Pastry Paradise is an Android application developed using Flutter. It allows users to purchase various pastries and cakes. The app includes features like Google and email authentication, push notifications, and utilizes Firebase for backend services.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Web Version](#web-version)
- [Contact](#contact)

## Features

- **User Authentication**
  - Google Authentication
  - Email Authentication

- **Notifications**
  - Push Notifications

- **Backend Services**
  - Firebase Firestore for data storage
  - Firebase Authentication
  - Firebase Cloud Messaging for push notifications

## Installation

### Prerequisites

- Flutter SDK: [Flutter installation guide](https://flutter.dev/docs/get-started/install)
- Firebase account: [Firebase Console](https://console.firebase.google.com/)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/sakibahmedshanto/pastryparadise.git
   cd pastry-paradise
   ```

2. Install dependencies:

   ```bash
   flutter pub get
   ```

3. Set up Firebase:

   - Create a new project in the [Firebase Console](https://console.firebase.google.com/).
   - Add an Android app to your Firebase project.
   - Follow the instructions to download the `google-services.json` file and place it in the `android/app` directory.
   - Enable Firebase Authentication and Firestore in the Firebase Console.

4. Run the app:

   ```bash
   flutter run
   ```

## Usage

1. **Authentication**:
   - Users can sign up or log in using Google or email.
   - The app will send push notifications to users about updates and promotions.

2. **Purchasing Pastries**:
   - Browse through a variety of pastries and cakes.
   - Select and purchase your desired items.
   - Receive notifications about your order status.

## Web Version

Pastry Paradise also has a web app version designed for mobile devices. You can access it [here](imas-pastry-paradise.web.app).



## Contact

For any questions or suggestions, please contact [sakibsanto57@gmail.com].

---

Feel free to customize the content as needed and replace placeholders with your actual details.

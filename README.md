# Modern Authentication UI - Flutter Assignment

A responsive User Interface for a Login, Register, and Forgot Password flow built with Flutter. This project demonstrates clean UI design principles, input validation, and efficient state management.

## 📱 App Screenshots

|                 Login Screen                  |                 Register Screen                  |                Forgot Password                 |
|:---------------------------------------------:|:------------------------------------------------:|:----------------------------------------------:|
| <img src="screenshots/login.png" width="200"> | <img src="screenshots/register.png" width="200"> | <img src="screenshots/forgot.png" width="200"> |

## 🛠 Tech Stack
* *Framework:* Flutter
* *Language:* Dart


## 💡 Key Features & Code Explanation


### 2. Form Validation
I used GlobalKey<FormState> and TextFormField instead of basic TextFields.
* *Why:* To ensure data integrity before processing.
* *How:* The login button checks _formKey.currentState!.validate() to ensure the email and password fields are not empty before proceeding.


### 4. Navigation
Used Navigator.push() for smooth transitions between the Login, Register, and Forgot Password screens.

---
Created by John Beloved Osemegbe Oregbemhe for [CSC 315]

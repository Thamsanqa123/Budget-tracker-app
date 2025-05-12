# Budget Tracker App

![App Logo](app/src/main/res/mipmap-xxxhdpi/ic_launcher.png) <!-- Add your logo if available -->

A personal finance management app for Android that helps users track expenses, manage budgets, and achieve savings goals.

## Features

- **User Authentication**
  - Secure login and registration
  - Email/password authentication
  - Social login integration (optional)

- **Expense Tracking**
  - Add expenses with categories
  - Attach receipt photos
  - View expense history

- **Budget Management**
  - Set monthly budgets
  - Category-specific limits
  - Visual spending progress

- **Reports & Analytics**
  - Spending trends visualization
  - Category-wise breakdowns
  - Custom date range filtering

- **Gamification**
  - Achievement badges
  - Savings milestones
  - Weekly/monthly challenges

## Screenshots

| Login Screen | Dashboard | Expense Entry |
|--------------|-----------|---------------|
| ![Login](screenshots/login.png) | ![Dashboard](screenshots/dashboard.png) | ![Expense](screenshots/expense.png) |

## Technologies Used

- **Kotlin** - Primary programming language
- **Android Jetpack Components**:
  - ViewModel
  - LiveData
  - Room Database
  - Navigation Component
- **Dependency Injection**: Hilt
- **UI**: Material Design 3
- **Charts**: MPAndroidChart
- **Image Handling**: Glide/Picasso

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/budget-tracker.git

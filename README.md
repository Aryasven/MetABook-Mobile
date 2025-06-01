# MetABook Mobile

A Flutter mobile application version of MetABook - a social platform for book lovers.

## Overview

MetABook Mobile is a cross-platform mobile application that allows users to:
- Create virtual bookshelves to organize their books
- Track reading progress and set reading goals
- Share reviews and recommendations with friends
- Discover new books through community recommendations
- Connect with other readers with similar interests

## Features

- **Authentication**: Email/password and Google Sign-In
- **Virtual Bookshelves**: Create and customize multiple bookshelves
- **Book Search**: Find books using Google Books API
- **Social Features**: Connect with friends, share shelves, and recommendations
- **User Profiles**: Customize your profile and reading preferences
- **Offline Support**: Access your shelves even without internet connection

## Technical Stack

- **Frontend**: Flutter
- **Backend**: Firebase (Authentication, Firestore, Storage)
- **APIs**: Google Books API for book data

## Getting Started

1. Clone this repository
2. Set up Firebase project and add configuration files
3. Run `flutter pub get` to install dependencies
4. Run `flutter run` to start the application

## Project Structure

- `lib/`: Main application code
  - `models/`: Data models
  - `screens/`: UI screens
  - `widgets/`: Reusable UI components
  - `services/`: Firebase and API services
  - `utils/`: Helper functions and utilities

## Development Roadmap

- [x] Project setup
- [ ] Firebase integration
- [ ] Authentication screens
- [ ] Book search functionality
- [ ] Bookshelf UI implementation
- [ ] User profile screens
- [ ] Social features
- [ ] Offline support
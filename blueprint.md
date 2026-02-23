# Product Bidding System - Blueprint

## 1. Project Overview

This document outlines the plan and progress for building a Flutter-based mobile application for a product bidding system. The app will allow users to register, browse products, place bids in real-time, and receive notifications. The backend will be powered by Firebase.

## 2. Core Features Implemented

*   **Firebase Integration:** Core setup for Firebase services.
*   **Authentication:** User registration and login using Firebase Authentication.
*   **Theming:** A modern, responsive theme with support for light and dark modes.
*   **Routing:** Declarative navigation using `go_router`.
*   **State Management:** Using `provider` for managing app-wide state like theme and user authentication status.
*   **UI Components:** Foundational UI components and screens.

## 3. Current Plan: Initial Project Setup

The current goal is to establish the foundational structure of the Flutter application.

### Steps:

1.  **Add Dependencies:** Integrate necessary packages from `pub.dev` for Firebase, state management, and UI enhancements.
    *   `firebase_core`: For basic Firebase integration.
    *   `firebase_auth`: For user authentication.
    *   `cloud_firestore`: For database interaction.
    *   `firebase_messaging`: For push notifications.
    *   `provider`: For state management.
    *   `go_router`: For navigation.
    *   `google_fonts`: For custom typography.
2.  **Initialize Firebase:** Configure the Android and iOS apps to connect to a Firebase project.
3.  **Implement Theming:** Create a `ThemeProvider` and define `ThemeData` for both light and dark modes, incorporating `google_fonts`.
4.  **Set Up Routing:** Configure `go_router` with initial routes for home, login, and registration screens.
5.  **Create Core Directory Structure:** Organize the project into logical folders (`auth`, `models`, `screens`, `services`, `widgets`) to ensure scalability and maintainability.
6.  **Build Initial Screens:** Develop basic placeholder UI for the main application screens (e.g., `LoginScreen`, `RegisterScreen`, `HomeScreen`).

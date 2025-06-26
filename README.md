Chingu - iOS Social Event Finder

Chingu is a prototype for an iOS mobile application designed to help university students discover, create, and join local campus events. The goal is to foster a stronger campus community by connecting students through shared interests and real-world activities.

This repository contains the complete front-end prototype built with SwiftUI.

Features

This prototype demonstrates a wide range of front-end features and modern UI/UX patterns:

User Sign-Up & Sign-In: A complete UI flow for new and returning user authentication.

Animated Splash Screen: A welcoming launch screen that establishes the app's brand.

Dynamic Event Feed: A scrollable list of campus events with a featured "Trending" section.

Filtering & Sorting: Users can filter events by category (e.g., "Sports", "Study Group") and sort them by date, popularity, or capacity.

Event Detail Page: A dedicated screen showing detailed information for a selected event.

Mock Chat System: A complete UI for a list of chat rooms and a detailed chat view with styled message bubbles.

Event Creation Form: A full-featured form for users to create and post their own events.

Dark Mode Support: The entire UI is fully compatible with both light and dark modes.

Interactive UI Animations:

Success Confirmation: A delightful animation on the sign-in button that confirms a successful login.

Smooth Transitions: Custom page transitions that make the app feel fluid and responsive.

Technologies & Concepts

This project is built entirely with modern Apple technologies and showcases several key concepts:

SwiftUI: The core declarative UI framework used for building the entire application.

Swift: The programming language used.

Xcode: The project is built and managed using Xcode 15 or newer.

MVVM-like Architecture: The code is organized by its purpose, separating Views, Models, and other components for clarity and maintainability.

State Management: Utilizes SwiftUI's built-in state management tools (@State, @Binding) to create a responsive and interactive UI.

Front-End Prototype: This project is currently a front-end prototype. It does not connect to a live backend server and uses mock data for display.


Getting Started
To run this project on your local machine, you will need a Mac with Xcode installed.

Prerequisites
macOS (Ventura 13.0 or newer recommended)

Xcode (version 15.0 or newer recommended)

How to Run
Clone the Repository

Bash

git clone https://github.com/Dkim0911/Chingu.git
cd Chingu
Open in Xcode
Navigate to the project folder and double-click the Chingu.xcodeproj file. This will open the project in Xcode.

Build and Run

At the top of the Xcode window, select an iOS Simulator you'd like to use (e.g., "iPhone 15 Pro").

Press the "Play" button (or use the shortcut Cmd + R) to build and run the application. The simulator will launch and you will see the Chingu app.

Future Work & Next Steps
This prototype lays the foundation for a full-featured application. The next major steps would involve:

Backend Integration: Connecting the front-end UI to a live backend API (like the Go server from the example) to handle:

Real user authentication.

Fetching and posting live event data.

Real-Time Chat: Implementing WebSockets or using a service like Firebase to enable live, real-time messaging between users.

Data Persistence: Storing user information, event RSVPs, and chat history in a remote database.

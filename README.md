# Turtle Up Tracking

### Table of Contents

1. [Product Description](#product-description)
2. [Technical Details](#technical-details)
   - [Frontend](#frontend)
   - [Backend](#backend)
   - [Database](#database)
   - [System Architecture Diagram](#system-architecture-diagram)
3. [Development Progress](#development-progress)
   - [Current App Design](#current-app-design)
4. [Direction and Prospects](#direction-and-prospects)
   - [Priorities](#priorities)
   - [Features](#features)
   - [Other Actions](#other-actions)

---

## Product Description

The Turtle Up Tracking mobile app allows users to track turtles in real time while also offering ways to support the Turtle Up organization. The app provides information about turtles, options for purchasing Turtle Up products and making donations, and access to additional resources about the organization.

## Technical Details

### Frontend:

- **Framework**: React Native
  - Framework for developing mobile applications (iOS and Android) on a single codebase
  - Bridges JavaScript (in our case TypeScript) code to platform-native components
- **Metaframework**: Expo
  - Framework built on top of React Native, a wrapper
  - Allows for prototyping and deployment without needing to set up native development environments like Xcode or Android Studio
  - **Expo Go**: Mobile app that allows for preview and testing in real time
- **Language**: TypeScript
  - JavaScript with static typing
- **Maps**: Google Maps API, react-native-maps
  - Maps APIs for displaying locations and paths

### Backend:

- **Go**
  - Mainly used for handling POST requests to send data to Firebase
  - Decided for future-proofing, has extensive documentation, allows for implementation of AI features

### Database:

- **Firebase**
  - Shared database with other Turtle Up group
  - Utilize Firebase SDK to handle GET requests to retrieve data
  - Decided for Firebase's efficient real-time updates to clients

### System Architecture Diagram:

![](images/capstone-turtle-up-month-1-architecture.png)

## Development Progress

### Current App Design:

- **Home**: General information on turtles the user has supported through purchasing the Turtle Up bracelets
- **Map**: Turtle locations and paths
- **Shop**: Purchase items and donate to Turtle Up
- **About**: Resources about Turtle Up

![](images/capstone-turtle-up-month-1.png)

## Direction and Prospects

### Priorities

- Finalize basic functionality of the app
- Implement sign-up, authentication, and database functionality
- Integrate Turtle Up resources (podcasts, donations, links, etc.)

### Features:

- **End of Month 2 Features**:

  - SSO: Users can create an account or link with an available external account (Google, iCloud, etc.)
  - Shop Page: Handling secure transactions
  - Map Integration: Ability to display static data on the map page.

- **Future Features**:
  - Biometric authentication
  - AI implementation
  - Webview integration of Turtle Up Education game

### Other Actions:

- Daily SCRUM meetings with both groups, regularly updating progress
- Team hackathon activity, possibly with other Turtle Up groups

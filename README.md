# HertzSoft Educare

HertzSoft Educare is a Flutter-based education management application designed for a modern learning ecosystem. The project focuses on helping students and trainers manage courses, batches, schedules, attendance, profile information, and communication in a clean digital interface.

This repository combines the working mobile application with design assets, planning documents, and a simplified schema overview to support development and future expansion.

## Overview

The app is structured around two primary user roles:

- Student portal
- Trainer portal

Each role has a tailored dashboard and set of features aimed at simplifying day-to-day education operations.

For students, the app supports course discovery, enrolled batch tracking, upcoming sessions, notification visibility, and personal profile management. For trainers, it supports batch oversight, lecture planning, attendance monitoring, and the management of a teaching schedule.

## Key Features

### Student Experience
- Welcome dashboard with profile context and quick access to important information
- Notifications and message indicators
- Course catalog with search and filter tools
- Enrolled batches and upcoming learning events
- Popular courses section with broader browsing opportunities
- Personal profile and editable contact details
- Detailed course and batch pages for academic tracking

### Trainer Experience
- Personalized trainer dashboard
- Ongoing and upcoming batch visibility
- Lecture schedule and calendar-style planning
- Batch listing and filtering
- Attendance and performance tracking support
- Trainer profile management
- Batch detail pages covering lecture history and progress

### Cross-Platform Foundation
- Flutter app built for mobile and web-based delivery
- Material design-based interface
- Shared preferences for lightweight local storage
- Google Fonts integration for a polished app identity
- Native splash screen support

## Project Structure

```text
HertzSoft/
├── App/
│   ├── hertzsofts_educare/
│   │   ├── android/
│   │   ├── ios/
│   │   ├── lib/
│   │   ├── assets/
│   │   ├── test/
│   │   ├── web/
│   │   ├── windows/
│   │   ├── analysis_options.yaml
│   │   ├── flutter_native_splash.yaml
│   │   ├── pubspec.yaml
│   │   └── README.md
│   └── v2/
├── figma/
├── images/
├── edu_app_schema.mermaid
├── Educare App Modules List.txt
└── README.md
```

### Main app folder
The core Flutter application lives in:

- `App/hertzsofts_educare`

This contains the actual app implementation, project configuration, platform folders, and asset definitions.

### Supporting planning documents
The repository also contains design and planning resources:

- `edu_app_schema.mermaid` — schema definition for the core user and academic entities
- `Educare App Modules List.txt` — feature and module breakdown for student and trainer screens
- `figma/` and `images/` — design inspiration and visual assets

## System Context

The project appears to be designed as an education-focused platform where users are organized into student and teacher accounts, with login history tracking and role-based relationships. The schema indicates a model where users can be identified as either students or teachers, with supporting data such as course/batch context, profile metadata, and authentication history.

This structure suggests a strong foundation for an academic platform that can be extended with:

- course management
- fees and billing records
- attendance tracking
- notifications and messages
- batch progression calendars
- admin dashboards
- analytics and reporting

## Tech Stack

- Flutter / Dart
- Material Design UI components
- Shared Preferences for local persistence
- Google Fonts for styling
- Platform-specific Android/iOS/web support
- Visual design assets and schema planning for future backend integration

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Flutter SDK (version compatible with the project configuration)
- Android Studio or Xcode for mobile development
- An emulator or physical device for testing

### Run the app

```bash
cd App/hertzsofts_educare
flutter pub get
flutter run
```

If you are using a specific device or emulator, Flutter will prompt you to choose a target. You can also run with a specific device ID if needed.

### Optional splash configuration

The project includes a native splash screen configuration:

```bash
flutter pub run flutter_native_splash:create
```

## Why This Project Matters

HertzSoft Educare demonstrates a practical educational application concept designed to support student engagement, trainer operations, and structured learning workflows. It is especially useful as a foundation for:

- student and teacher portals
- course enrollment systems
- academic scheduling applications
- training batch management tools
- educational dashboards and reporting systems

## Future Expansion Ideas

This repository is a strong starting point for a larger education platform. Potential next steps include:

- backend integration with Firebase, Supabase, or a custom API
- authentication and role-based access control
- course and batch database design
- payment and fee management
- real-time classroom and attendance monitoring
- push notifications and messaging
- admin management tools

## Notes

This repository currently includes both the application code and the documentation/design artifacts needed to understand the product vision. The project is well-suited for academic, training, or startup-style product prototyping and can be expanded into a full learning management system.

## Contributing

Contributions are welcome as the project grows. If you are extending the app, consider maintaining consistency in:

- UI design patterns
- module organization
- feature documentation
- testing coverage
- platform compatibility

---

Built with Flutter for a modern education platform experience.

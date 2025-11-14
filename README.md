# Timely

> A collaborative planner that turns your handwritten schedules into smart, digital events.

**Timely** is a cross-platform app that bridges the gap between the freedom of a paper journal and the power of a digital calendar. It's designed for those who think best with a pen in hand and need a simpler, more intuitive way to organize life, track wellness, and stay focused.

## What is this?

Digital planners can be finicky on tablet devices, on the other hand traditional paper bullet journals are flexible and personal. However the concept is "dumb." It can't send notifications, sync across your devices, and be shared easily.

Timely gives the best of both worlds. It provides a digital canvas where you can **draw your own schedule**, **write your to-dos**, and **log your habits by hand**. Timely intelligently parses your handwriting and transforms it into real digital events.

Timely can:
- Sync across all devices
- Send notifications for events your _drew_ up
- Lets your collaborate and share schedules with friends

It provides a simpler, zen, and more mindful approach to productivity, built to help your organize your life in a way you probably wouldn't imagined.

## Key Features
- **Analog-to-digital Scheduling**: The core of Timely. Draw a block on your daily, weekly, or monthly view, write "ECON101 @ 1:00-2:15," and Timely automatically creates that event in your calendar.
- **Basic Calendar Functions**: Create recurring events (like classes or appointments), set to-dos, and get reminders, all synced across all platforms.
- **Life Tracking**: Timely includes integrated modules for:
  - **Goal tracking**: Log and visualize progress on your habits.
  - **Body tracking**: Keep track of your workouts, food/calorie intake, and body weight.
  - **Time tracking**: Monitor sleep duration and screen time to look back on habits.
- **Journaling**: A dedicated space for personal thoughts and reflections, tied directly to your days and mood.
- **Cross-platform**: Native support for Android (stylus-enabled devices like the Boox or Kindle)

## Made with

![Swift](https://img.shields.io/badge/swift-F54A2A.svg?style=for-the-badge&logo=swift&logoColor=white) ![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)

## Roadmap

<details>
<summary><strong>🗺️ Click to view the Project Roadmap (Android/Web First)</strong></summary>
<br>
Our development strategy prioritizes Android (Kotlin) and Web (React) to reach a v1.0 launch, with iOS (Swift) development planned to begin afterward.

### Phase 1: Core Backend & Android POC
**Goal:** Prove the core "analog-to-digital" concept works on Android.
- [ ] **[Backend]** Setup Firebase: Authentication, Firestore, and Storage.
- [ ] **[Backend]** Design V1 database schema for users, events, and drawings.
- [ ] **[Android - Kotlin]** Project setup (Jetpack Compose) and native drawing canvas.
- [ ] **[Android - Kotlin]** Integrate Google's ML Kit for handwriting recognition (POC).
- [ ] **[Android - Kotlin]** Basic local storage for saving drawings and parsed events.

### Phase 2: Synced MVP (Android + Web)
**Goal:** Get Android and Web authenticated and syncing data with Firebase.
- [ ] **[Backend]** Implement user authentication (Email/Google) and secure Firestore rules.
- [ ] **[Android - Kotlin]** Integrate Firebase SDK (Auth, Firestore) and sync data.
- [ ] **[Android - Kotlin]** Build basic calendar and event views.
- [ ] **[Android - Kotlin]** Add digital (non-drawing) event creation/editing.
- [ ] **[Web - React]** Build the initial React app, integrate Firebase auth, and build a read-only calendar view that syncs with Firestore.

### Phase 3: Beta (Android + Web Feature Parity)
**Goal:** Build out the full wellness and utility feature set on Android and Web.
- [ ] **[Backend]** Setup Firebase Cloud Messaging (FCM) for notifications.
- [ ] **[Android - Kotlin]** Integrate FCM for push notifications.
- [ ] **[Web - React]** Implement web push notifications.
- [ ] **[Android/Web]** Implement recurring events logic.
- [ ] **[Android/Web]** Build the Journaling module (UI and backend).
- [ ] **[Android/Web]** Build the V1 Habit Tracking module (UI and backend).
- [ ] **[Android - Kotlin]** Implement "Schedule Templates" to save/reuse hand-drawn layouts.
- [ ] **[Ops]** Setup Google Play Console for closed beta.

### Phase 4: v1.0 Launch (Android + Web)
**Goal:** Polish and launch the Android and Web apps with V1 collaboration.
- [ ] **[Backend]** Implement logic for "following" and public/private schedules.
- [ ] **[Android/Web]** Build UI for V1 collaboration (view friends' public schedules).
- [ ] **[Android/Web]** Complete wellness modules: Body Tracking and Time Tracking.
- [ ] **[Android/Web]** Add basic charts/graphs for wellness data.
- [ ] **[Android/Web]** Conduct full UI/UX design polish and create onboarding flows.
- [ ] **[Ops]** Launch on the Google Play Store and a public web domain.

### Phase 5: iOS Development & Future Features
**Goal:** Begin iOS development to achieve parity and introduce new global features.
- [ ] **[iOS - Swift]** Begin iOS Development:
    - [ ] Project setup (SwiftUI) and native drawing canvas (`PencilKit`).
    - [ ] Integrate Apple's Vision framework for handwriting recognition (POC).
    - [ ] Integrate Firebase SDK (Auth, Firestore) and sync all data.
    - [ ] Build all core app views (Calendar, Journal, Habits, etc.) to match Android/Web.
    - [ ] Implement notifications, templates, and collaboration features.
    - [ ] UI/UX polish and launch on the Apple App Store.
- [ ] **[All Platforms] Future Vision:**
    - [ ] Real-time collaborative editing (shared journals/schedules).
    - [ ] AI-powered wellness/productivity insights.
    - [ ] Integrations: Google Calendar, Apple Health, Google Fit.
    - [ ] Advanced handwriting AI (natural language understanding).
    - [ ] A public API for third-party developers.

</details>

## Getting Started

### License
This project is licensed under the GNU General Public License v3.0.

### Contact
Jacob Lontoc - jacobc.lontoc@gmail.com

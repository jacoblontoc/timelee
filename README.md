# Timely (iOS & Android App)

> A collaborative planner that turns your handwritten schedules into smart, digital events.

**Timely** is a cross-platform app (iOS, Android, and Web) that bridges the gap between the freedom of a paper journal and the power of a digital calendar. It's designed for those who think best with a pen in hand and need a simpler, more intuitive way to organize life, track wellness, and stay focused.

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
- **Cross-platform**: Native support for iOS (Apple Pencil) and Android (stylus-enabled devices like the Boox)

## Made with

![Static Badge](https://img.shields.io/badge/React-19.2.0-blue?style=flat&logo=react) ![Static Badge](https://img.shields.io/badge/React%20Native-0.82.1-blue?style=flat&logo=react) ![Static Badge](https://img.shields.io/badge/Firebase-14.19.0-orange?style=flat&logo=firebase) ![Static Badge](https://img.shields.io/badge/MongoDB-8.2-green?style=flat&logo=mongodb)

## Roadmap

<details>
<summary><strong>🗺️ Click to view the Project Roadmap</strong></summary>
<br>
We are currently in active development. This roadmap outlines our planned features, and we welcome all contributions.

### Phase 1: Proof of Concept (Local-Only)
- [ ] Basic React Native project setup.
- [ ] Implement a drawing canvas view.
- [ ] Integrate a handwriting recognition service (e.g., ML Kit, Vision).
- [ ] Create a simple parser to identify events and times from text.
- [ ] Save drawings and parsed events to local device storage.
- [ ] Display parsed events on a basic calendar view.

### Phase 2: Core MVP (Sync & Web)
- [ ] Implement Firebase backend (Authentication, Firestore, Storage).
- [ ] Add user sign-up, login, and Google Sign-In.
- [ ] Design and implement Firestore database schema.
- [ ] Sync all data (events, drawings) between devices using Firebase.
- [ ] Build the initial React web application with auth and a read-only calendar view.
- [ ] Add digital event creation/editing (in addition to drawing).
- [ ] Implement a basic, synced to-do list.

### Phase 3: Beta (Wellness & Utility Features)
- [ ] Add support for recurring calendar events.
- [ ] Implement push notifications for event reminders (via Firebase Cloud Messaging).
- [ ] Build the journaling module, linking entries to specific days.
- [ ] Build the V1 habit tracking module.
- [ ] Create "Schedule Templates" to allow users to save and reuse their hand-drawn layouts.
- [ ] Set up TestFlight and Google Play Console for beta testing.

### Phase 4: v1.0 Public Launch (Collaboration)
- [ ] Implement V1 collaboration: allow users to follow friends and view their public schedules (read-only).
- [ ] Complete the wellness modules: Body Tracking (calories, food, weight) and Time Tracking (sleep).
- [ ] Add basic charts and graphs to visualize wellness data.
- [ ] Conduct a full UI/UX design polish for a clean, professional feel.
- [ ] Launch on the Apple App Store and Google Play Store.

### Future (Post-v1.0)
- [ ] Real-time collaborative editing (shared journals, schedules).
- [ ] AI-powered insights on wellness and productivity.
- [ ] Integrations with Google Calendar, Apple Health, etc.
- [ ] Advanced handwriting AI (natural language understanding).
- [ ] A public API for third-party developers.

</details>

## Getting Started

### License
This project is licensed under the GNU General Public License v3.0.

### Contact
Jacob Lontoc - jacobc.lontoc@gmail.com

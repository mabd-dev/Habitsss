# Changelog

All notable changes to this project will be documented in this file.
This project follows Semantic Versioning.

# 0.6.x - Publishing on Github Releases

## 0.6.2 - 2026-03-12

### ✨ New

- App Review: Added custom app review dialog to receive user feedback and listen to any complains 

### 🔧 Updates

- **BoardView Screen**: removed monthly switcher 


## 0.6.1 - 2026-03-03

### ✨ New

- Show `app update` dialog in home screen


### 🐛 Bug Fixes

- Fix: home screen boards does not auto-reload after importing data


## 0.6.0 - 2026-02-23

### 🔄 Updated

- Improved settings screen UI
- Internal Changes


### 🛠 Fixed

- HomeScreen error handling: reset loading state when error occur.


# 0.5.x – Architecture Refinement & UX Polish (Mid–Late 2025)

## [0.5.3] - 2025-08-17
This release focused on architecture cleanup and improving check-in UX.

### ✨ Added

- Swipe to delete check-ins
- Tap check-ins to edit
- Show today’s log amount on board cards
- Haptic feedback when saving logs

### 🔄 Improved

- Moved insights & stats into dedicated Analytics screen
- Improved month switcher in Analytics
- Refined board layout and UI responsiveness

### 🧱 Internal

- Major module restructuring for improved scalability
- Refactored dependency injection container
- Moved analytics & error logging into services layer
- Cleaned feature module organization
- Improved module documentation

### 🛠 Fixed

- Add Widget button in settings was not responding


## [0.5.2] – 2025-07-13

Release Focus: Sync refinement and subscription system cleanup.

### 🔄 Improved

- Manual cloud sync button (feature-flag controlled)
- Cleaned unused remote config keys
- Removed legacy subscription tier code
- Improved import behavior (update change date on import)

### 🛠 Fixed

- Cloud sync reliability issues
- Onboarding “Create First Board” button
- Removed unnecessary back button in step-by-step onboarding


## [0.5.1] – 2025-06-14

### ✨ Added

- Grid or list layout for boards
- Notification-based board check-in button

### 🛠 Fixed

- Crash when opening app from notification

## [0.5.0] – 2025-06-10

Release Focus: Reminders and remote configuration control.

### ✨ Added

- Board reminders system
- Remote-config based feature toggling
- Top app bar notification indicator

## 🔄 Improved

- Simplified statistics (available to all users)
- CI workflow optimization

## 🛠 Fixed

- Gesture issues in drag mode
- Bottom sheet dismissal behavior

***

# 0.4.x – Onboarding & Subscription Refinement

## [0.4.1]

- Migrated to libs.versions.toml dependency management
- Expanded onboarding flow with guided questions
- Added configuration service screen


## [0.4.0]

### Major Features:

- Step-by-step board creation
- Manual data sync (controlled visibility)
- Improved paywall experience
- Refactored authentication & subscription data layers

Result: First subscription conversion after onboarding improvements.

***

# 0.3.x – Widgets, Cloud Backup & Advanced Analytics

This phase focused on power-user features and system integration.

## Major Additions

- Home screen widgets (with auto-refresh worker)
- Google sign-in
- Cloud backup & restore
- In-app feature requests (Canny integration)
- Analytics screen
- Theme customization (including AMOLED mode)
- End-of-day reminders
- Advanced heatmap improvements
- Board ordering & customization

## Stability Improvements

- Multiple reminder scheduling fixes (Android 12+ compatibility)
- Crash fixes related to workers and DI initialization
- Navigation and month-handling corrections
- Widget interaction refinements

This phase significantly improved reliability and expanded ecosystem integration.

***

# 0.2.x – Monetization, Remote Config & User Feedback Loop

This stage marked the transition from prototype to monetized product.

## Key Additions

- Subscription system (RevenueCat & BillingClient)
- Paywall implementation
- Firebase anonymous authentication
- Remote configuration system
- Habit archiving
- Haptic feedback interactions
- Habit descriptions & minimum quantity tracking

## Iteration Based on Feedback

- UI refinements for heatmap & paywall clarity
- Improved analytics instrumentation
- Subscription eligibility logic
- Focus and keyboard handling fixes across devices

This phase introduced real user segmentation, feature flagging, and subscription experimentation.

***

# 0.1.x – Initial Launch & Core Foundation

## Initial Release (0.1.0)

- Onboarding flow
- Habit creation & editing
- Precise logging
- Settings
- Feature request integration

## Early Improvements

- Monthly & weekly progress charts
- Firebase analytics integration
- Paywall & subscription setup
- Data migration fixes
- JSON import/export support

This phase established the core product and architecture foundation.

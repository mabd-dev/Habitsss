# Habitsss – Habit Tracker (Android)

<div align="center">
  <img src="./assets/app-icon.png" alt="App Icon" width="120">
</div>

[![Changelog](https://img.shields.io/badge/changelog-available-blue)](CHANGELOG.md)

Habitsss is a modern, native Android habit tracking app focused on streaks, analytics, and long-term consistency.

Originally launched on Google Play in November 2024, Habitsss reached 350+ active users and included subscription-based features before the Play Store account was suspended due to new identity verification requirements.

The app is now distributed directly via GitHub Releases.

> This repository contains release builds and documentation only.  
> The source code remains private.

---

## 📥 Download

👉 **Download the latest APK**
- Minimum Android version: API 28+
- Architecture: Universal APK
- Signed release build
- 100% free to use

If you find issues, please open one in the **Issues** tab.

---

## ✨ Features
- ✅ Habit boards with customizable frequency tracking
- 📊 Rich analytics with streak tracking and visualizations
- 🔔 Smart reminder & notification system
- 📆 History log with custom date filtering
- 🧩 Modular architecture (built for long-term scalability)
- 🔒 Local-first data storage
- 🎯 Designed for long-term habit consistency

---

## Features Demo
<table>
  <tr>
    <td width="50%">
      <img src="./media/thumbnails/onboarding.jpg" alt="Onboarding Demo" width="300">
    </td>
    <td width="50%">
      <h3>Onboarding</h3>
        <ul>
          <li>Personalized onboarding questions to better understand user needs</li>
          <li>Guided step-by-step board creation for first-time users</li>
        </ul>
      <a href="./docs/demos/onboarding.md"><strong>🎥 Watch demo</strong></a>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>Boards</h3>
        <ul>
          <li>Switch between grid and list layouts on the home screen</li>
          <li>Reorder boards with drag and drop</li>
          <li>Archive boards for later access</li>
          <li>Log check-ins for today or for a specific date and time</li>
          <li>Add notes to your check-ins</li>
        </ul>
      <a href="./docs/demos/boards.md"><strong>🎥 Watch demo</strong></a>
    </td>
    <td width="50%">
      <img src="./media/thumbnails/boards.jpg" alt="Boards View" width="300">
    </td>
  </tr>
  <tr>
    <td width="50%">
      <img src="./media/thumbnails/board-editor.jpg" alt="Board Editor" width="300">
    </td>
    <td width="50%">
      <h3>Board Editor</h3>
        <ul>
          <li>Edit board metadata: title and description</li>
          <li>Customize board color using presets or a color picker (color wheel, HEX, RGB)</li>
          <li>Configure custom unit with minimum check-in amount</li>
          <li>Advanced reminders managements: add, edit, enable, disable, or remove</li>
        </ul>
      <a href="./docs/demos/board-editor.md"><strong>🎥 Watch demo</strong></a>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>📊 Analytics</h3>
        <ul>
          <li>Line chart showing current month progress</li>
          <li>Key statistics: best day, max per day, average per day, consistency, and more</li>
          <li>Current vs previous month comparison chart</li>
          <li>Interactive line chart with custom date range</li>
        </ul>
      <a href="./docs/demos/analytics.md"><strong>🎥 Watch demo</strong></a>
    </td>
    <td width="50%">
      <img src="./media/thumbnails/analytics.jpg" alt="Analytics" width="300">
    </td>
  </tr>
  <tr>
    <td width="50%">
      <img src="./media/thumbnails/widget.jpg" alt="Settings" width="300">
    </td>
    <td width="50%">
      <h3>Widget</h3>
        <ul>
          <li>View boards directly from the widget</li>
          <li>Add check-ins without opening the app</li>
          <li>Tap a board to open its dedicated screen</li>
          <li>Use the Home button to quickly launch the app</li>
        </ul>
      <a href="./docs/demos/widgets.md"><strong>🎥 Watch demo</strong></a>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>⚙️ Settings And Personalization</h3>
      <ul>
          <li>Customizable app accent color</li>
          <li>Theme support: Light, Dark, and AMOLED modes</li>
          <li>Archived boards management (restore or permanently delete)</li>
          <li>Data import and export capabilities</li>
          <li><b>Contact Support:</b> Opens email client with prefilled diagnostic information (user ID, device manufacturer, etc.)</li>
          <li><b>Send Debug Logs:</b> Export and attach application logs for troubleshooting</li>
      </ul>
      <a href="./docs/demos/settings.md"><strong>🎥 Watch demo</strong></a>
    </td>
    <td width="50%">
      <img src="./media/thumbnails/settings.jpg" alt="Settings" width="300">
    </td>
  </tr>
</table>

---

## 🏗 Architecture & Engineering Highlights

Habitsss was built as a production-grade application using:
- **Kotlin**
- **Jetpack Compose**
- **MVVM**
- **Multi-module architecture**
- **Custom Dependency injection method**
- **Room database**
- **GitHub Actions CI**
- Modular feature-based structure
- Clean separation between domain, data, and presentation layers

The project was designed to scale and potentially evolve into a Kotlin Multiplatform app.

---

## 📈 Product Journey
- Started development: November 2024
- Released on Google Play
- Reached 350+ users
- Implemented subscriptions & analytics
- Ran marketing experiments
- Collected real-world usage feedback

The app was removed from Google Play after new developer identity verification requirements required public physical address disclosure.

Rather than comply, I chose to distribute the app independently.

Habitsss remains fully functional and free.

---

## 🛣 Future

Habitsss may continue evolving in the future. Possible directions:
- Kotlin Multiplatform expansion
- Desktop support
- Advanced analytics
- Open-sourcing selected modules

For now, the focus is preservation and accessibility.

---

## 🐛 Issues & Feedback

If you encounter:
- Bugs
- UI issues
- Feature suggestions

Please open an issue.

Feedback is welcome.

---

## 📄 License

All rights reserved.  
The application is free to use, but the source code is not public.









## CricStatz 📱🏏

**CricStatz** is a mobile app (built with Flutter) to make it easy for cricket lovers to **store, track, and view cricket stats** for their matches with friends, local leagues, or practice sessions.

This project is open source and beginner‑friendly. The guide below walks you through **setting up Flutter from scratch**, so anyone can get started and contribute.

---

## 1. Prerequisites

- **A computer**: Windows, macOS, or Linux
- **Git** installed  
  - Download from `https://git-scm.com/downloads`
- **A code editor** (recommended: Visual Studio Code)  
  - Download from `https://code.visualstudio.com/`

---

## 2. Install Flutter

The official Flutter docs are excellent and always up to date, so **follow them first**, then come back here:

- **Flutter installation guide**: `https://docs.flutter.dev/get-started/install`

Follow the steps for **your OS** (Windows/macOS/Linux). In short, you will:

1. Download the Flutter SDK for your platform.
2. Add Flutter to your system `PATH`.
3. Run `flutter doctor` to check for any missing dependencies.

In a terminal (Command Prompt / PowerShell / bash), run:

```bash
flutter doctor
```

Make sure there are **no major issues** (or fix what Flutter suggests in the output).

---

## 3. Set up an Editor (VS Code recommended)

If you use **VS Code**:

1. Open VS Code.
2. Go to **Extensions**.
3. Install:
   - **Flutter** extension
   - **Dart** extension

These will give you code completion, debugging, and Flutter tools directly inside the editor.

---

## 4. Clone this Repository

In a terminal, run:

```bash
git clone https://github.com/<your-username>/CricStatz.git
cd CricStatz
```

> Replace `<your-username>` with the actual GitHub username or org where this repo lives.

---

## 5. Get Flutter Dependencies

Once you are inside the project folder (`CricStatz`), run:

```bash
flutter pub get
```

This downloads all required Dart/Flutter packages for the app.

---

## 6. Run the App

You can run on:

- An **Android emulator** or **physical Android device**
- An **iOS simulator** or **physical iPhone** (macOS only)

Steps:

1. Make sure a device or emulator is running.
2. From the project root, run:

```bash
flutter run
```

Flutter will build the app and launch it on the connected device/emulator.

---

## 7. Contributing

Contributions are welcome! If you are a beginner, don’t worry — this project is meant to be friendly.

**Basic workflow (simple version):**

1. **Fork** the repo on GitHub (this creates your own copy).
2. **Clone** your fork to your computer.
3. Make your changes on your fork’s `main` branch.
4. Run and test the app:

```bash
flutter run
```

5. Commit and push your changes to your fork:

```bash
git add .
git commit -m "Describe your change"
git push origin main
```

6. Open a **Pull Request** from your fork’s `main` to the original repo’s `main`.

---

## 8. Project Goals (High Level)

Some ideas for CricStatz:

- **Create teams and players**
- **Record match scorecards** (runs, wickets, overs, strike rate, economy, etc.)
- **Store past matches** and view history
- **Simple charts / stats** for players and teams

This section will evolve as the app grows. Feel free to open issues with ideas or suggestions.

---

## 9. Need Help?

If you get stuck:

- Check the Flutter docs: `https://docs.flutter.dev`
- Open an issue in this repo describing:
  - Your OS
  - Flutter version (`flutter --version`)
  - The command you ran
  - The error message you see

Happy coding and happy cricket! 🏏


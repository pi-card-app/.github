# Pi-Card — Volleyball Scoreboard & Community App

**排球計分板與社群應用程式**

> A modern, intuitive volleyball scoreboard app with real-time player rotation tracking, live game casting, and multi-language support. Built with Flutter.

![Pi-Card Overview](./profile/Picard.png)

<!-- Site: Coming Soon -->

<!-- Demo Video: Coming Soon -->

---

## Introduction

Keeping score in volleyball—especially in official matches—requires tracking rotations, substitutions, libero replacements, and timeouts. Traditional paper scoresheets are error-prone and hard to follow. Pi-Card solves this with:

- **Tap-to-Score Interface** — One tap to add a point, with instant visual feedback
- **Rotation Tracking** — Visual court diagram showing all 6 positions for both teams
- **Live Casting** — Share your game to spectators using a simple cast code

---

## Use Cases

Pi-Card is designed for volleyball players, coaches, and referees:

- **Casual Games**:
  - Quick setup with no lineup required
  - Simplified rules, free substitutions
  - Perfect for pickup games and practice matches

- **Official Matches**:
  - Full 5-set match support with proper point limits (25/15)
  - Player rotation visualization with serving indicator
  - Libero tracking with automatic position restrictions
  - Substitution management with 6-sub limit per set

- **Live Spectating**:
  - Cast your game with a unique code
  - Spectators can follow the score in real-time
  - No account required to watch

- **Multi-Language Support**:
  - 🇺🇸 English
  - 🇯🇵 日本語
  - 🇹🇼 繁體中文

---

## Screenshots

| Home | Scoreboard | Court View |
|:----:|:----------:|:----------:|
| ![Home](./profile/screenshots/home.png) | ![Scoreboard](./profile/screenshots/scoreboard.png) | ![Court](./profile/screenshots/court.png) |

| Lineup Setup | Settings | Live |
|:------------:|:--------:|:----:|
| ![Lineup](./profile/screenshots/setup_lineup.png) | ![Settings](./profile/screenshots/settings.png) | ![Live](./profile/screenshots/live.png) |

## Tech Stack

| Category | Technology |
|----------|------------|
| Framework | Flutter / Dart |
| State Management | Riverpod |
| Backend | Firebase (Auth, Firestore) |
| Navigation | Go Router |
| Local Storage | Hive |
| Architecture | Clean Architecture + SOLID |

---

## Getting Started

```bash
# Clone the repository
git clone https://github.com/pi-card-app/pi-card.git

# Install dependencies
cd pi-card
flutter pub get

# Run the app
flutter run
```

---

## License

MIT License

---

<p align="center">
  🏐 Made with ❤️ for the volleyball community
</p>

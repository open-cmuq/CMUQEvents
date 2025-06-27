# YallaEvents Mobile App

Welcome to the home of **YallaEvents**, a hybrid Flutter application that keeps students in the loop about every campus happening in real time.

## Why YallaEvents?
Students often miss out on talks, workshops, and club socials because the information is scattered. YallaEvents pulls approved events straight from the university event registry and presents them in a single, friendly feed. Less searching, more showing up.

## Core Features
- **Live Event Feed** – automatic sync with the university event system once an event is approved
- **Smart Filters** – pick by category, time, location, or whether there is food
- **Personal Calendar** – add events to the device calendar with one tap
- **Push Reminders** – optional reminders so users never miss the fun
- **Social Sharing** – share events with classmates in two clicks

## Tech Stack
| Layer | Tool |
|-------|------|
| UI    | Flutter 3.x (Dart) |
| Design | Figma (design file in `/design` folder) |
| State  | Riverpod |
| Data   | REST integration with the university event API |
| Auth   | University SSO (OAuth 2) |

> **Timeline** – One month for the MVP. We move fast and ship often.

## Getting Started

### Prerequisites
- Flutter SDK ≥ 3.22
- Dart ≥ 3.2
- Android Studio or Xcode command-line tools
- A configured device or emulator

### Clone & Run
```bash
# 1. Grab the code
git clone https://github.com/YallaEvents/mobile.git
cd mobile

# 2. Install packages
flutter pub get

# 3. Launch the app
flutter run
```

## Development Tasks
| Phase | Goals |
|-------|-------|
| Week 1 | Set up project, deliver login screen, connect to staging API |
| Week 2 | Build event list, implement filters |
| Week 3 | Calendar integration, push notifications |
| Week 4 | Polish UI, internal beta, bug fixes |

The full roadmap lives in the GitHub Issues tab.

## Contributing
Pull requests are welcome. For major changes, open an issue first so we can discuss the scope.

### Branch Strategy
- `main` – production ready
- `dev` – active sprints
- `feature/*` – individual features

Run `flutter analyze` and `flutter test` before submitting a PR.

## License
This project is licensed under the MIT License. See `LICENSE` for details.

## Acknowledgments
Created during a reflection session on the London trip by:
- Abdulrahman
- Gustavo
- Diyorbek Ibragimov

## Contact
For questions, reach out in the `#yallaevents` Slack channel or email **events-dev@university.edu**.

_Stay updated. Show up. Yalla._

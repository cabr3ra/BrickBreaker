# Brick Breaker

Welcome to the Brick Breaker Game, a classic arcade-style game built with Flutter and the Flame game engine.
In this game, you control a bat to keep a ball in play while breaking bricks.
The goal is to break all the bricks without letting the ball fall off the screen.


## 📂 Project Structure

brick_breaker/
|- lib/
|- main.dart
|- src/
|- brick_breaker.dart
|- config.dart
|- components/
|- ball.dart
|- bat.dart
|- brick.dart
|- components.dart
|- play_area.dart
|- widgets/
|- game_app.dart
|- overlay_screen.dart
|- score_card.dart
|- pubspec.yaml


## 🚀 Features

- **main.dart**: Entry point of the application. It initializes and runs the game.
- **brick_breaker.dart**: Core game logic and main game loop.
- **config.dart**: Configuration constants such as game dimensions, colors, and other settings.
- **components/**: Contains game components like the ball, bat, bricks, and play area.
- **widgets/**: Contains Flutter widgets used for the game's UI like the game app, overlay screens, and score card.
- **pubspec.yaml**: Dependency configuration file.


## 📦 Dependencies

- **flame:** A lightweight game engine for Flutter.
- **google_fonts:** To apply custom fonts to the game's UI.
- **flutter_animate:** For animations in overlay screens.


## 🛠️ How to Run

1. Clone this repository.
2. Navigate to the project directory.
3. Run `flutter pub get` to install dependencies.
4. Run `flutter run` to start the app.
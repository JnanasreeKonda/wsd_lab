# Work System Design Lab Experiments App

A Flutter-based mobile application designed for Work System Design (WSD) and Ergonomics laboratory experiments. This tool provides structured modules, experimental procedures, and interactive assessments for industrial engineering students.

## Features

* **Experiment Modules**: Complete documentation for lab tasks:
    * **Preliminary Method Study**: Pen, 3-pin plug, and bicycle pedal assembly.
    * **Ergonomic Variables**: Hand-finger movement, coordination, and learning curves.
    * **Physical Capacity**: Work/recovery cycles via bicycle ergometer and treadmill.
    * **NIOSH Lifting Equation**: RWL and Lifting Index calculations.
    * **Environmental Factors**: Visibility and illumination studies.
    * **Anthropometry**: Body dimension variability for sustainable design.
* **Interactive Assessment**: Built-in True/False quiz covering all lab principles.
* **Visual Guides**: Step-by-step diagrams and images for hardware setup.

## Getting Started

### Prerequisites
* [Flutter SDK](https://docs.flutter.dev/get-started/install)
* Dart SDK
* Android Studio / Xcode (for mobile emulators)

### Installation & Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/jnanasreekonda/wsd_lab.git](https://github.com/jnanasreekonda/wsd_lab.git)
    cd wsd_lab
    ```

2.  **Install dependencies:**
    ```bash
    flutter pub get
    ```

3.  **Run the app:**
    ```bash
    flutter run
    ```

## Project Structure

* `lib/main.dart`: UI logic and navigation.
* `lib/question.dart`: Data structure for laboratory quizzes.
* `Images/`: Asset directory for experimental setups and diagrams.
* `pubspec.yaml`: Project dependencies and configuration.

## Development

This project was built using:
* **Framework**: Flutter
* **Language**: Dart
* **Platform Support**: Android, iOS, and Web

## License
This project is for educational purposes within the WSD Lab.

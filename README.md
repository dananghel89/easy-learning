# Easy Learning

[![Java](https://img.shields.io/badge/Java-100%25-orange?logo=java)](https://www.java.com)
[![GitHub last commit](https://img.shields.io/github/last-commit/dananghel89/easy-learning)](https://github.com/dananghel89/easy-learning/commits/master)

A simple Android application project from 2014, built with Java, aimed at providing an easy learning experience.

## About

This repository contains the source code for the **Easy Learning** Android app. It was originally created in June 2014 as a learning project for Android development. The project includes basic Android components, user functions, and support for older Android versions via the Android Support Library.

**Note:** This is an older project and may require updates to build and run with modern Android development tools.

## Features

*   Basic user authentication flow (Login/Register) via `UserFunctions` class
*   Simple and clean user interface (as per early Android design guidelines)
*   Built with **Java**
*   Uses **Android Support Library (JAR)** for backward compatibility

## Technologies Used

*   **Language:** Java
*   **Platform:** Android (Targeting older versions, likely API levels 15-19)
*   **IDE:** Eclipse with ADT (as indicated by `.project` and `.classpath` files)
*   **Libraries:** Android Support Library (compatibility JAR)

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

*   **Java Development Kit (JDK)** (Version 7 or 8 recommended for this project)
*   **Android SDK** (You can use Android Studio to manage SDKs)
*   **Git** (to clone the repository)

### Installation

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/dananghel89/easy-learning.git
    ```

2. Open in Android Studio / Eclipse:
   * If using Android Studio, choose "Import project (Eclipse ADT, Gradle, etc.)" and select the cloned folder.
   * If using a modern Android Studio, you may be prompted to migrate the project to use Gradle. It's recommended to do so.

3. Resolve Dependencies:
   * The `libs/` folder contains an Android support JAR. Ensure it's added to your project's build path if you're not using a build system like Gradle.

4. Build and Run:
   * Connect an Android device or start an emulator, then run the project.

## Project Structure (as of 2014)

* `src/`: Contains the Java source code (ro.ase.ism package)
* `res/`: Contains all Android resources (layouts, drawables, values)
* `libs/`: Contains external libraries, such as the Android Support Library
* `bin/`: Generated output folder (compiled classes and APK)
* `gen/`: Generated Java files (e.g., R.java)

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.

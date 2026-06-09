# ComposeTry - Modern Android Interview Template

A robust, production-ready Android project template built with **Jetpack Compose**, **Kotlin 2.4.0**, and **AGP 9.2.1**. This project is optimized for technical interviews, demonstrating best practices in modular architecture, reactive programming, and automated testing.

## 🛠 Tech Stack & Tooling

### Core Toolchain
*   **Kotlin 2.4.0**: Utilizing the latest language features and the new Compose Compiler.
*   **Android Gradle Plugin (AGP) 9.2.1**: Leveraging "Built-in Kotlin" support for faster build times and reduced configuration overhead.
*   **Version Catalog**: Centralized dependency management via `libs.versions.toml`.

### UI & Architecture
*   **Jetpack Compose**: 100% declarative UI using the latest Compose BOM (`2026.05.01`).
*   **Jetpack Navigation**: Type-safe navigation for Compose.
*   **Hilt**: Standardized Dependency Injection for Android.
*   **Lifecycle & ViewModel**: Reactive state management with `StateFlow` and `collectAsStateWithLifecycle`.

### Data & Networking
*   **Retrofit 3.0.0**: The latest major version of the industry-standard networking library.
*   **OkHttp 5.3.2**: Advanced networking interceptors and logging.
*   **Room 2.8.4**: Local persistence with full Coroutines and Paging support.
*   **DataStore**: Modern, asynchronous alternative to SharedPreferences for key-value storage.
*   **Paging 3.5.0**: Efficient loading of large datasets in Compose.
*   **Coil 2.7.0**: Performance-focused image loading.

### Testing Suite (Interview Ready)
*   **MockK**: Modern mocking library designed specifically for Kotlin.
*   **Google Truth**: Fluent assertions for more readable and maintainable tests.
*   **Kotlinx Coroutines Test**: Robust utilities for testing asynchronous logic and `ViewModel` state.
*   **JUnit 4**: Core unit testing framework.

## 🏗 Key Architectural Patterns
*   **Single Activity Architecture**: All UI flows managed via Navigation Compose.
*   **MVVM / MVI**: Unidirectional Data Flow (UDF) patterns.
*   **Repository Pattern**: Clean abstraction between data sources (Network/Local) and the UI.
*   **State Hoisting**: Best practices for managing and delegating Composable state.

## 🚀 Getting Started
1. Open the project in the latest **Android Studio Ladybug (or newer)**.
2. The project uses AGP 9.2.1, ensuring high compatibility with modern build systems.
3. Check `libs.versions.toml` for the full dependency list and versions.

## 📝 Interview Quick-Start
This project is configured to Serve as a Template application for Android Interviews
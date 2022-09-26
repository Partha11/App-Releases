<img src="app/src/main/res/drawable/app_logo.png" alt="App Logo"/>

## Clean architecture using MVVM architecture
- Model (for database, API and preferences)
- View (for UI logic, with DataBinding)
- ViewModel (for business logic)
- Workers (for background processing)
- Broadcast Service (for triggering specific services depending on user events)

## Dependencies
- Dependency injection (with [Hilt](http://google.github.io/hilt/))
- Google [Material Design](https://material.io/blog/android-material-theme-color) library
- Android architecture components to share ViewModels during configuration changes
- [Jetpack Navigation](https://developer.android.com/guide/navigation) for single activity design
- Kotlin Coroutines
- Room Database for offline capabilities
- Retrofit
- [Desugaring](https://developer.android.com/studio/write/java8-support-table) for Java 8 API supports
- Resource defaults
    - themes.xml - app themes
    - colors.xml - colors for the entire project

# WeatherAPI

WeatherAPI App
WeatherAPI is a SwiftUI app that provides dynamic weather updates. It uses the MVVM architecture and Combine framework to fetch and display weather information. The app also dynamically changes images based on the weather conditions and supports a minimum iOS version of 14.
Features
● Dynamic Weather Updates: The app fetches and displays current weather information.
● Image Changes Based on Weather Conditions: The app changes its background
images according to the current weather condition.
● MVVM Architecture: The app is built using the Model-View-ViewModel (MVVM)
architecture.
● Combine Framework: The app uses the Combine framework for managing
asynchronous events.
Requirements
● iOS 14.0 or later
● Xcode 12.0 or later
Usage
1. On launch, the app will request location permission to fetch the weather data for your current location.
2. The app will display the current weather information, including temperature, weather condition, and an image that matches the weather condition.
Architecture
The WeatherAPI app follows the MVVM architecture pattern:
● Model: Represents the weather data fetched from the API.
● View: The SwiftUI views that display the UI.
● ViewModel: The intermediary between the Model and View, responsible for business
logic and data formatting.

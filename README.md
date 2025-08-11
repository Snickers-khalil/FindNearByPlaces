# Find Nearby Places

This is a native Android application built in Java that helps users find specific types of places around their current location using Google Maps and the Google Places API.

### Key Features:

1.  **Display Current Location**: When you open the app, it requests permission to access your location. Once granted, it pinpoints your current position on the map with a green marker.
2.  **Search for a Specific Address**: There is a search bar at the top where you can type any address. The app will find that location and place a purple marker on the map.
3.  **Find Nearby Places**: The app has dedicated buttons to find:
    *   **Hospitals**: Shows nearby hospitals.
    *   **Schools**: Shows nearby schools.
    *   **Restaurants**: Shows nearby restaurants.
4.  **Google Maps Integration**: The app uses the Google Places API to fetch the nearby locations and displays them as markers on the map within a 10,000-meter (10km) radius of your current location.

### How to Use:

1. Clone the repository.
2. Open the project in Android Studio.
3. Add your Google Maps API key in the `google_maps_key` string resource.
4. Build and run the application on an Android device or emulator.

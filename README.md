# React-Native-Expo-Maps

A React Native Expo app demonstrating how to display a map with user location and markers using `react-native-maps` and `expo-location`.

<div style="display: flex; justify-content: space-around;">
    <img src="./assets/images/Image1%20(3).jpg" alt="App Screenshot 1" style="width: 30%;"/>
    <img src="./assets/images/Image1%20(2).jpg" alt="App Screenshot 2" style="width: 30%;"/>
    <img src="./assets/images/Image1%20(1).jpg" alt="App Screenshot 3" style="width: 30%;"/>
</div>


## Features

- 🗺️ Displays a map centered on Colombo, Sri Lanka.
- 📍 Shows the user's current location on the map.
- 📌 Includes predefined markers with titles and descriptions.
- 🧭 Supports zooming and panning.
- 💬 Opens a modal with marker details on press.
- 🧭 Navigate to marker location from the modal via external map.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/SasadaSaumya/React-Native-Expo-Maps.git
   cd React-Native-Expo-Maps
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Install Expo CLI globally if you haven't already:
   ```bash
   npm install -g expo-cli
   ```

## Running the App

Start the Expo development server:
```bash
expo start
```

You can then run the app on an emulator or your physical device using the Expo Go app.

## Dependencies

* [react-native-maps](https://github.com/react-native-maps/react-native-maps) – For rendering the map.
* [expo-location](https://docs.expo.dev/versions/latest/sdk/location/) – To access the device location.
* [react-native-modal](https://github.com/react-native-modal/react-native-modal) – (if used) For enhanced modal functionality.
* [Linking API](https://reactnative.dev/docs/linking) – To open external map apps like Google Maps.

## Notes

* The app requests foreground location permission at launch.
* The initial map region centers around Colombo with custom markers.
* Marker click opens a styled modal with title, description, and a button to open external maps for directions.

---

Feel free to contribute, suggest improvements, or raise issues!

---

**Author:** Sasanda Saumya  
**GitHub:** [https://github.com/SasadaSaumya](https://github.com/SasadaSaumya)

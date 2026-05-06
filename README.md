# Drive-Pro
Sollutionns Drive Pro is a high-performance telemetry and tracking application designed specifically to turn your smartphone into an advanced on-board computer. It combines real-time cartographic visualization with accurate consumption and distance metrics.
Here are the pillars that define the app:
1. Geospatial Tracking System
The heart of the app is the integration with the Leaflet API in "Dark Mode" mode. It not only shows where you are, but uses the watchPosition function to create data persistence.
Route View: As you move around, the app draws a blue line (polyline) that represents your exact trail.
Auto-Follow: The map camera tracks the vehicle automatically, keeping the focus on the direction of movement (ideal for use on dashboard supports).
2. Telemetry and Consumption Panel
Unlike an ordinary GPS, Drive Pro focuses on the health and efficiency of travel:
Fuel Calculation: Based on the distance traveled and the average consumption configured, it tells how many liters were spent in real time.
Tank Management: It has a 9-bar visual indicator (BMW digital panel style) that estimates the remaining range based on the current fuel level.
3. PWA (Progressive Web App) Experience
The app was structured to be installed directly on the operating system (Android/Samsung), eliminating the browser interface:
Full Screen 9:16: Optimized for long screens like the S24, taking advantage of every pixel of the OLED screen.
Offline operation: Thanks to Service Worker, the basic tools load even in internet signal shadow zones.
4. Ergonomic "Cockpit" interface
The design was designed for automotive use:
High Contrast: Dark colors with accents in BMW Blue and Orange to prevent visual fatigue and ensure quick reading in sunlight.
Quick Action Buttons: The "Start" button and the "Centralize Map" button are large and positioned for easy thumb reach.
Summary of Functionalities

Apple Maps Home Rebuild — Geolocation & Search Integration

This project recreates the Home screen of Apple Maps, including real-time geolocation and a search bar.
The goal was to understand and replicate some of the core behaviors of the official app, while deepening my knowledge of SwiftUI and MapKit.

During development, I “deconstructed” Apple Maps to study how its components interact. I initially ran into several issues working with Xcode, but through research—and with help from Alfonso—I eventually understood how everything fits together and managed to rebuild the entire interface.

Key Features:
	•	Interactive Map powered by MapKit
	•	Real-time geolocation via CoreLocation
	•	Integrated Search Bar with dynamic results
	•	Minimal UI inspired by Apple Maps
	•	Location permission handling
	•	Clean SwiftUI architecture with UIKit bridging

  Project Goals:
  •	Understand how iOS handles location services.
	•	Rebuild the main Apple Maps interface for learning purposes.
	•	Explore the integration between SwiftUI and UIKit/MapKit.
	•	Practice designing a clean, coherent, and intuitive interface.

  Why this project ?
  I chose Apple Maps because I’ve always been curious about its features and internal structure.
Rebuilding part of its main screen helped me understand:
	•	how user location is tracked and updated
	•	how location search works
	•	how MapKit is wrapped into SwiftUI
	•	best practices for UI and architecture in modern iOS apps
  
  Technologies Used:
	•	Swift
	•	SwiftUI
	•	MapKit
	•	CoreLocation
	•	Xcode
  
  Project Structure:
	•	MapView — UIKit wrapper for MapKit
	•	LocationManager — handles real-time user location
	•	SearchBarView — search input and result handling
	•	HomeView — main layout inspired by Apple Maps

  What I Learned:
	•	The difference between the native SwiftUI Map and a UIKit MapKit wrapper
	•	How location permissions are requested and managed
	•	How to synchronize UI, user position, and map interaction
	•	The value of reverse-engineering an existing app to rebuild complex behavior

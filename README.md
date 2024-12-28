# ONBOARD App Simulation Script Overview
## Introduction
This script is designed to simulate functionalities of the 'ONBOARD app'. It focuses on enhancing emergency response efficiency by calculating the fastest route and estimated arrival time for emergency vehicles to an accident scene generated randomly within the San Jose area.

## Key Features
### Coordinate Retrieval
API Used: Google Maps Geocoding API
Functionality: Fetches latitude and longitude from given addresses to precisely locate destinations and origins.
### Random Location Generation
Purpose: Establishes a simulated accident site by generating a random location within predefined boundaries.
Tools: Uses Nominatim for initial geocoding, enhancing the randomness and realism of the simulation.
### Estimated Time of Arrival (ETA) Calculation
API Used: Google Maps Distance Matrix API
Functionality: Calculates the travel time from multiple fire stations to the accident scene and determines the quickest arrival time.
Additional Feature: Calculates ETA to a user-specified additional destination, providing flexibility in operations.
### User Interface
Interactivity: Allows users to input a destination and receive back the calculated ETA, making the simulation interactive and user-friendly.
Output Customization: Employs color coding to highlight important textual information, thereby improving readability and user engagement.

## Conclusion
This script provides a realistic simulation of emergency response scenarios, potentially aiding in training and operational planning for real-world applications. It showcases how APIs can be leveraged to create effective and interactive tools for emergency management.

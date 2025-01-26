# TRAVEL ALARM 🎯


## Basic Details
### Team Name: CodeTrio


### Team Members
- Member 1: Nivethtitha H D - LBS Institute Of Technology For Women
- Member 2: Reshmi Raj S - LBS Institute Of Technology For Women
- Member 3: Sneha Elza David - LBS Institute Of Technology For Women

### Hosted Project Link
https://code-trio.vercel.app/

### Project Description
The Travel Alarm is a web application designed to enhance your travel experience by providing location-based reminders. It utilizes the Geolocation API to track your current location in real-time. You can set your desired destination and choose an alarm distance (in kilometers). As you approach your destination within the chosen distance, an alarm is triggered to notify you. A user-friendly interface allows you to easily enter your destination, select an alarm distance, and view your current distance from the destination. This feature helps reduce travel anxiety and ensures you never miss your stop.

### The Problem statement
Travelers often miss their intended stop, causing delays, wasted time, and extra costs. This happens when they unknowingly overshoot their destination.

### The Solution
The Travel Alarm app is your digital travel buddy! ✈ It uses your phone's GPS to gently nudge you with a friendly alert when you're getting close to where you need to be. No more frantic searches or awkward backtracking – just sit back, relax, and let Travel Alarm keep you on track.

## Technical Details
### Technologies/Components Used
For Software:
- HTML,CSS ,JAVASCRIPT
- N/A 
- Leaflet.js
- OpenCagedata API, Audio feature for Alarm Sound , ChatGPT


### Implementation
For Software:
HTML: The layout is structured using basic HTML elements like inputs, buttons, and div containers.
CSS: Custom styling is applied for a clean and modern look. The map and input sections are designed to be responsive.
JavaScript:
Geolocation API: Tracks the user's real-time location.
Leaflet.js: Integrates an interactive map to show the user's location and destination.
OpenCage API: Converts destination names into geographical coordinates.
Distance Calculation: Uses the Haversine formula to calculate the distance between the user and their destination.
Audio Alert: Plays an alarm sound once the user is within the defined distance from their destination.

# Installation
Prerequisites:
A web browser (Google Chrome, Firefox, etc.)
An internet connection (for API requests and loading Leaflet tiles)
1. Clone this repository to your local machine:
bash
Copy
Edit
git clone https://github.com/your-username/travel-alarm.git
2. Navigate to the project directory:
bash
Copy
Edit
cd travel-alarm
3. Open index.html file in a web browser:
Simply double-click the index.html file to open it in your default browser

# Run
Open the application: Launch the index.html file in your browser.
Enter your destination: Type the name of the location you're traveling to in the input box.
Set the alarm distance: Choose a distance (2 km, 5 km, or 10 km) for the alarm trigger.
Start tracking: Click the "Start Tracking" button to begin location tracking.
Wait for the alert: The app will calculate your real-time location and compare it to your destination. If you are within the chosen distance, an alarm will trigger, and you will be notified that you are near your destination.
Stop the alarm: Once the alarm is triggered, you can stop it by clicking the "Stop Alarm" button.



# Screenshots (Add at least 3)
![Travel Alarm SS1]("C:\Users\Reshmi Raj\Desktop\Codetrio\CodeTrio\Screenshots\Traval Alarm SS1.png")
The Main Interface of the Web App is shown here


![Travel Alarm SS2]("C:\Users\Reshmi Raj\Desktop\Codetrio\CodeTrio\Screenshots\Traval Alarm SS2.png")
Selection of your destination and at what distance you want the alarm to go off is shown here

![Travel Alarm SS3]("C:\Users\Reshmi Raj\Desktop\Codetrio\CodeTrio\Screenshots\Traval Alarm SS3.png")
In this Screenshot the alarm is ringing while displaying that we are close to our destination as well as a button to stop the alarm

# Diagrams
![Workflow]("C:\Users\Reshmi Raj\Desktop\Codetrio\CodeTrio\Screenshots\workflow.jpg")
It shows the process from the user input, through geolocation fetching and distance calculations, to the triggering of the alarm and control options for the user.

### Project Demo
# Video
[Add your demo video link here]
*Explain what the video demonstrates*



## Team Contributions
-Nivethitha H D: Conceptualization, HTML, CSS
-Reshmi Raj S: API Integration, Web App Testing, Alarm Audio Implementation
-Sneha Elza David: JavaScript Development, General Editing
---
Made with ❤️ at TinkerHub

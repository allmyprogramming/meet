#Achievement 4 Project:
 Meet App

#Objective
 To build a serverless, progressive web application (PWA) with React using a
 test-driven development (TDD) technique. The application uses the Google
 Calendar API to fetch upcoming events.

# Meet App - Given-When-Then Scenarios

### 1️⃣ Filter Events by City
**Given** the user is on the main page of the app,  
**When** they enter a city name in the search bar,  
**Then** the app should display only the events happening in that city.

### 2️⃣ Show/Hide Event Details
**Given** the user sees a list of events,  
**When** they click on an event's "Show Details" button,  
**Then** the app should expand to show more details about that event.  
**And** when they click "Hide Details," the details should collapse.

### 3️⃣ Specify Number of Events
**Given** the user is on the main page,  
**When** they enter a number in the "Number of Events" field,  
**Then** the app should display only that number of events.

### 4️⃣ Use the App When Offline
**Given** the user has previously loaded the app while online,  
**When** they lose their internet connection,  
**Then** the app should still show previously loaded event data.

### 5️⃣ Add an App Shortcut to the Home Screen
**Given** the user is using a mobile browser that supports PWA,  
**When** they choose to add the app to their home screen,  
**Then** the app should install as a Progressive Web App (PWA) and be accessible like a native app.

### 6️⃣ Display Charts Visualizing Event Details
**Given** the user is viewing the app,  
**When** they navigate to the statistics or analytics section,  
**Then** the app should display charts showing event data, such as event popularity by city.
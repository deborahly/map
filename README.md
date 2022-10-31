# MAPTY (workout-map)

### CONCEPT
Mapty is an application to register running and cycling workouts on a map. In addition to register the workout location, it also saves the workout date, distance, duration and either cadence or elevation gain, depending on the workout type.

App deployed in: [https://mapty-delight.netlify.app/](https://mapty-delight.netlify.app/)

### PROJET CHARACTERISTICS 
Being a simple project, it comprises all the application structure in a single class object. It uses the browser's Geolocation API to determine the user's current location, and a third-part library (Leaflet) to display the map and add map markers. The workouts are saved in the browser local storage.

### KEY FEATURES
- Navigate through the map by dragging it or zooming in and out
- Click on any point in the map to register a workout, then fill the form with the session information (type, distance, duration and cadence/elevation gain); once submitted, the workout will be displayed on the map and on a list
- On the list, click on any workout to be directed to its location on the map
- On the map, click on the "x" icon in the workout description box in order to remove it from the storage

### INSTALL AND RUN
Clone the project from GitHub:

```bash
git clone https://github.com/deborahly/workout-map.git
cd workout-map
```

To run the application, open the index.html file with Google Chrome or other browser. The app requires that the browser knows the user location, so click "accept" when prompted.

*This project was made during the course* The Complete JavaScript Course 2022: From Zero to Expert!*. Although an assignment project, I coded it entirely by myself, not copying a single line from sources provided by the course.*

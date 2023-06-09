## CarFinder: Privacy Policy

The CarFinder app is a simple app that allows users to save location data against one or more cars and to display these locations on a map.

### Data Inputs

The user is able to add new cars (by entering name and description fields) and can mark a car's current location (latitude, longitude, altitude and timestamp) which the app reads from the device's local geo-location service.

### Data Storage

The car and location data are stored in the file system on the local device. The app does not make use of any remote services for data storage or any other purpose.

### Data Outputs

The car and location data is displayed to the user when requested and is also passed to the Google Maps app on the same device to allow the user to view the car's location on a map. The app does not require internet connectivity to fetch the location data and Google Maps can display the user and car's relative locations when the device is off-line. There are some more advanced features of Google Maps that do require the internet, for example to update map details and to provide directions. It would be down to user discretion to remain in airplane mode and forego these features if privacy is a concern. This policy covers the CarFinder app itself and does not cover privacy policies for Google Maps.   

### Permissions Required

The following permissions are required by the app in order to function:

<br/>

| Permission | Why it is needed |
| :---: | --- |
| `android.permission.ACCESS_FINE_LOCATION` | This is required to allow the app to request the fine location of the device to save against the car after parking. |

 <hr style="border:1px solid gray">

### Conclusion

Due to its disconnected design, the Car Finder app provides a high degree of user data privacy, even if the device is connected to the internet. This is simply because the app does not connect to any remote servers and stores all car and location data locally.


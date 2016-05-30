## GPStracker
Add this permission in the manifest:

`android.permission.ACCESS_COARSE_LOCATION` or `android.permission.ACCESS_FINE_LOCATION`

And instantiate the object in your class:



`GPSTracker gpstracker = new GPSTracker(context);`


`gpstracker.getLatitude();`

`gpstracker.getLongitude();`

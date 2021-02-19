# MarkerWithAddressGoogleMap
Google maps API has provided awesome functionalities for users, Like Search places, Pick address by tapping on map, Distance and time duration between two coordinates on map.

I am going to show you how to get coordinates information(Address, Country…) by dragging map and adjusting marker on fixed position.

##### Screenshot
 Home screen with Map                       | On Tap on map & after getting Address                      |
:------------------------------------------:|:-------------------------------------------:
<img src="screenshot/without address.jpg" width="200">|<img src="screenshot/with address.jpg" width="200">|


##### Enable API for google maps android API and google places API for android as shown below

<img src="screenshot/goole map api.jpeg">

##### Get API key from Credentials as shown below.

<img src="screenshot/api credential.png">


Add API key inside google_maps_api.xml that is automatically created.

    <resources>
      <string name="google_maps_key" templateMergeStrategy="preserve" translatable="false">AIzaSyDR1gZOOD7UP9Q_lsXc5s5kVhvCQyrsO1s</string>
    </resources>

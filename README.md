# FlickrBrowserApp
    * This is a Filckr Photo Viewer App. The Android Studio project is Attached with it.
    * You can directly open it in Android Studio and run it on your Android Device.

Working:
* It takes the tags entered by user as input.
* creates a URL with those tags with default language as a english or en-us.
* Obtains a JSON Format File from the Flickr API.
* Parses it down into an ArrayList of Photos
* It also Uses Picasso as a third party library to download images in the background and updating them when they download.
* The Picasso library maintains the cache of downloaded images so rotation of device is not a problem.


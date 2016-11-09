# CloudRail SI Node.JS SDK changelog

* **2.10.0**
  * Introduced new interface called Business Cloud Storage
  * Amazon S3 has been added as a new service implementing Business Cloud Storage
  * Microsoft Azure has been added as a new service implementing Business Cloud Storage
  * Backblaze has been added as a new service implementing Business Cloud Storage
  * Rackspace has been added as a new service implementing Business Cloud Storage

* **2.9.3**
  * Small fixes to error reporting of some services
  * Facebook integration now uses newest version of the Facebook API
  
* **2.9.2**
  * Fixed an issue where a timeout would keep code using the library running indefinitely
  
* **2.9.1**
  * Added Egnyte as a new service, implementing the CloudStorage interface. 
    It does not support retrieval of user login, user name, available and 
    used space or thumbnails since the API exposes no such information yet.
  * Fixed bugs where GoogleDrive and OneDrive would not return ImageMetaData
    on elements retrieved through getChildren()
  
* **2.9.0**
  * The services in the CloudStorage interface now have an additional method to get thumbnails
  * The CloudMetaData objects now have additional dimension information for images
  
* **2.8.1**
  * Fixed an issue where an Error was thrown when logging out an already logged out instance of Box
  
* **2.8.0**
  * BREAKING: License key is now mandatory
  * Bugfixes for Box and Dropbox integrations

* **2.7.0**
  * BREAKING: The RedirectReceiver's callback function has a Node-style signature now
  * Added standard implementation for a RedirectReceiver with "electron" framework
  * Minor bugfixes
  
* **2.6.2**
  * Added standard implementation for local RedirectReceiver
  
* **2.6.1**
  * Made SendGrid integration more robust by updating to API v3
  
* **2.6.0**
  * Added "exists" function to "CloudStorage" interface
  * Added optional license key integration  
  
* **2.5.3**
  * Fixed incompatibility with older Node versions
  * Better quality of error messages  
  
* **2.5.2**
  * Bugfix to have errors contain messages  
  
* **2.5.1**
  * Compile to ES5 instead of ES6 for compatibility reasons
  * Minor bugfixes
    
* **2.5.0**
  * Included "Social" interface
  * Added space allocation information to "CloudStorage"  
  
* **2.4.0**
  * Initial release (Non-minor version numbers between SDKs for different platforms used to be synchronized)





  

  




Base64 Encoded Apps
==================

Proof of concept illustrating that an app can be stored as a URL in its entirety. There are [certain limits](http://technomanor.wordpress.com/2012/04/03/maximum-url-size/) to how many characters can be entered as a URL or stored as a bookmark, but when building micro applications, this isn't a concern. This example uses [dgileadi's Zepto Data Binding repo](https://github.com/dgileadi/zepto-data-binding) as the app being stored.  

## Untested Benefits

* Entirely bypass the iOS App Store for selling/distributing locally stored HTML5 applications
 
> Ask the user to "Add to Homescreen" to download application. The application is now stored as a bookmark on the homescreen.

* The assets are loaded from the disk without ever trying to talk to a server. **No 304's**.


## Untested Limitations

* Application size limit
* Unsure if performance is better or worse
* Updating is difficult or impossible
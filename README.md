# bookmyshow-notify

Get notified by mail whenever upcoming movie tickets are open for booking in BookMyShow

Change variables LOCATION, TIME_ZONE, MOVIE_NAME and MOVIE_LANG accordingly in app.js.

Eg:
```javascript
var LOCATION = 'CHEN'; //HYD, CHEN
var TIME_ZONE = process.env.TZ;
var MOVIE_NAME = 'Baahubali';
var MOVIE_LANG = 'Telugu';
```

Before running App xoauth2 tokens have to be filled along with 'mailOtions' variable in mail.js
Gmail xoauth2 tokens can be generates using Google APIs Console.
Refer : http://masashi-k.blogspot.in/2013/06/sending-mail-with-gmail-using-xoauth2.html

<!---
Cached View: http://webcache.googleusercontent.com/search?q=cache:http://masashi-k.blogspot.in/2013/06/sending-mail-with-gmail-using-xoauth2.html 
Just in case ;)
-->

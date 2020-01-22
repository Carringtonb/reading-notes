# Past Present and Future of Local Storage

* Historically, web applications have had none of these luxuries. Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:
    * Cookies are included with every HTTP request
        * Slows down your web application
        * Sends Data uncrypted
    * Cookies are limited to about 4 KB of data

### History of local storage hacks

* Beginning had Iternet Explorer
    * 2002 Adobe introduces Flash 6
    * 2006 Flash 8 introduces ExternalInterface
    * 2007 Google launches *Gears*
    * 2009 dojox.storage comes around and can auto detect Flash, Gears, AIR, and early HTML5
* Then HTML5 comes around and changes the game.
* HTML5 uses JavaScript to store data in **Key/Value** pairs.
* *Data is stored as strings. If you are storing something other than a string, you’ll need to coerce it yourself when you retrieve it.*

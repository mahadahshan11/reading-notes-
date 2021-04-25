# “The Past, Present, and Future of Local Storage for Web Applications”


**A BRIEF HISTORY OF LOCAL STORAGE HACKS BEFORE HTML5** 
 
 * 1) Microsoft was the first one to invent DHTML Behaviors to store data and one of thses behaviors was *userData*. this behavior allows web pages to store 64 KB of data per domain. 

 * 2) Adobe interduced a feature in Flash 6 known *Local Shared Objects* which allows flash objects to store up to 100 KB. 

 * 3) Brad Neuberg developed an early prototype of a Flash-to-JavaScript bridge called *AMASS* and the then Brad rewrote *AMASS* and modefiy it to *Dojo Toolkit* which can store each domain 100 KB for free.

 * 4) Google lunched *GEARS* which can store unlimited amount of data per domain. 

 **INTRODUCING HTML5 STORAGE**
  
* 1) it is a way for web pages to store named key/value pairs locally, inside the client web browser. this data is keopt and stored even after the user navigate away from the web site. and the data stored are not transmitted to the remote web server. 

**USING HTML5 STORAGE** 

* 1) since the storage in HTML5 s based on pairs of key/value. the named key is a string and it can include strings/booleans/integers/floats. you can retrive thses strings of data by using functions. 

**TRACKING CHANGES TO THE HTML5 STORAGE AREA**

* 1) to keep track of the changes that occure to storage area, you must trap the storage event. and then fire or call the event if there are no named keys, the storage event will not fire because nothing is changed in the storage area. 

**LIMITATIONS IN CURRENT BROWSERS**

* 1) the single limitation in HTML5 storage is that each data type inside the data strings (flaots ,integers) are saved as characters which can really add up in the storage. 

**HTML5 STORAGE IN ACTION**

* 1) the advantage of HTML5 storage is that is can save the progree locally within the browser itself even after you close the browser. the demonstration page remmeber your exact position and action up untillyou left the browser. 
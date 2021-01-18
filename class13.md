# Local Storage For Web Applications History

* With any HTTP request, cookies are used, thereby       slowing down your web application by unnecessarily transmitting the same data over and over. 
* With each HTTP request, cookies are used, transmitting data unencrypted over the internet (unless your entire web application is served over SSL) 

* Cookies are limited to about 4 KB of data, which is sufficient to slow down your request. 


There was just Internet Explorer in the beginning. Or at least, Microsoft wanted the world to think that way. To that end, Microsoft created a great deal of things as part of the First Great Browser Wars and used them in Internet Explorer, their browser-to-end-all-browser-wars. One of these things was called DHTML Behaviors, and userData was called one of these behaviors.
In 2002, in Flash 6, Adobe implemented a feature that acquired the unfortunate and inaccurate name of "Flash cookies." The feature is properly recognized as Local Shared Objects within the Flash environment. In short, it allows Flash objects per domain to store up to 100 KB of data. An early prototype of a Flash-to-JavaScript bridge named AMASS (AJAX Massive Storage System) was developed by Brad Neuberg, but it. 
But what is storage for HTML5? Simply put, inside the client web browser, it's a way for web pages to store named key/value pairs locally. Like cookies, even though you navigate away from the page, close your browser tab, exit your browser, or what you have, this data remains. This data is never transmitted to the remote web server, unlike cookies (unless you go out of your way to send it manually).
You can trap the storage event if you want to programmatically keep track of when the storage area changes. If setItem(), removeItem(), or clear() is called and anything actually changes, the storage event is fired on the window object. For example, if you set an object to its current value or call clear() when no named keys are available, the storage event will not fire because there is no actuall.


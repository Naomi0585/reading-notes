# Introduction to Persistance With Local Storage 

Developers would use **Local Storage** for a web application to keep their data and store the state of their interface when refreshing the page so the information doesn't reset instead. 
Although, we might not want to keep *all* of our data recorded on webpages. Personal information such as credit card info, passwords or other sensitive data should not be stored in yor local storage. 

In the `localStorage` we can only save strings. `localStorage` provides a simple JS API for persisting key-value pairs in the browser. Key value pairs could be stored in cookies but we wouldn't want to do that. The easiest way to use `localStorage` is to treat it like a regular object. 
# Infinite-Scroll
Inspired by: http://ravikiranj.net/drupal/201106/code/javascript/how-implement-infinite-scrolling-using-native-javascript-and-yui3

- No dependencies
- Tested in Chrome 17, IE7, Firefox 11, Android 2.3 Browser, iPad 2 with IOS5

## Usage
``` js
var options = {
  distance: 50,
  callback: function(done) {
    // 1. fetch data from the server
    // 2. insert it into the document
    // 3. call done when we are done
    done();
  }
}
    
// setup infinite scroll
infiniteScroll(options);
```

## How ReactNative Works
* The way it works is that there is local dev server that runs on local system and serves a bundle containing all the JS needed 
 to run the app.
* Standardized the API, don't need to learn two platform extensively.
* Debugging capability 
* Native 

## Architecture 
* At its core ReactievNative is a bridge that native code calls JS and vice versa.
* Steps
** Execution always starts in Native
** AppRegistry.runApplication('MyApp', {});
** Native code calls the JS function by passing app id and empty map over custome JSON based protocol bridge 
** Calls b/w native and JS are asyncronous 

* One big difference is that React Native runs the JavaScript code in a separate thread,
 so the user interface does not block and animations should be silky and smooth.
* 

## Working with ReactNative
* Get ready with  Andrioid and iOS setup
* 

# Questions
* Is ReactiNative application code runs in WebView ? No , its JS running in a VM and controlling native UI



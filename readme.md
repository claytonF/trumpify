# trumpify
<h2>Trumpify.js is a javascript framework that allows you to implement the policies of President Donald Trump on any DOM element.</h2>

#### Create a trumpify object
```
let trumpify = new Trumpify();
```
### Features will include: 

#### .wall() method
`trumpify.wall()` will build a wall along the southern border of any element assigned the .wall() method which currently only accepts one argument `trumpify.wall('mexico')`. This feature will be updated with new arguments in later releases.

If an element or variable is of type Muslim it will first go through an extensive vetting process before being permanently deleted from the DOM

#### .torture() method
`trumpify.torture()` accepts an array e.g. [waterboarding,sleepDeprivation,sensoryDeprivation] .torture() can be used on any DOM element and will randomly return an object {confession:true} or {confession:false}

#### .women() method
`trumpify.women(arg)` currently accepts a single argument and returns the string "grab them by the " + arg;

#### .repeal() method
Accepts legislation string and returns a promise which is resolved by either directly handling the response or if it goes worse than expected, blame the media, DC politicians or any other group who doesn't blindly support Trump's presidency.
```
trumify.repeal('OBAMA_CARE')
  .then(function(response){
    // handle media and public outcry here
  })
  .catch(function(error){
    // if it all goes to crap, blame it on mediaObject or corruptWashingtonArray
  });
```

I am currently actively seeking developers to contribute to the framework. Feel free to fork the repo and apply to your country.





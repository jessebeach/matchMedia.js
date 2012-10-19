#matchMedia() polyfill

## test whether a CSS media type or media query applies

* **Authors**:Jesse Renée Beach
* Based on matchMedia.js by Scott Jehl, Paul Irish, Nicholas Zakas

## Usage

#### test 'tv' media type
    if (matchMedia('tv').matches) {
      // tv media type supported
    }

### test a mobile device media query
    if (matchMedia('only screen and (max-width: 480px)').matches) {
      // smartphone/iphone... maybe run some small-screen related dom scripting?
    }

#### test landscape orientation
    if (matchMedia('all and (orientation:landscape)').matches) {
      // probably tablet in widescreen view
    }

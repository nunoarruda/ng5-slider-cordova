# ng5-slider + cordova.js issue

## Install and run

1. `npm install -g cordova`
2. `cd cordova-app`
3. `npm install`
4. `cordova run browser`

## Steps to reproduce

1. Open http://localhost:8000/index.html, this file does not load `cordova.js`
2. Test the slider, notice that it behaves as expected
3. Open http://localhost:8000/index-cordova.html, this file does load `cordova.js`
4. Test the slider, notice that it behaves strangely. `cordova.js` is interfering with the slider but why and how?

rn-assert-sample
================

power-assert / unassert sample with React Native

Screen Shots
------------

| assert | power-assert |
|--- | --- |
| <img src="https://raw.githubusercontent.com/januswel/rn-assert-sample/images/images/ios-assert.png" width="320" /> | <img src="https://raw.githubusercontent.com/januswel/rn-assert-sample/images/images/ios-power-assert.png" width="320" /> |

| assert | power-assert |
|--- | --- |
| <img src="https://raw.githubusercontent.com/januswel/rn-assert-sample/images/images/android-assert.png" width="320" /> | <img src="https://raw.githubusercontent.com/januswel/rn-assert-sample/images/images/android-power-assert.png" width="320" /> |

To Run
------

```sh
yarn
react-native run-ios
// or
react-native run-android
```

In order to run without power-assert, delete following codes in .babelrc, and then `npm start -- --reset-cache`.

```json
  "env": {
    "development": {
      "presets": [
        "power-assert"
      ]
    },
    "production": {
      "plugins": [
        "unassert"
      ]
    }
  }
```

# react-native-capichi-camera

## Getting started

`$ npm install react-native-capichi-camera --save`

### Mostly automatic installation

`$ react-native link react-native-capichi-camera`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-capichi-camera` and add `CBCapichiCamera.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libCBCapichiCamera.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import io.mylibrary.CBCapichiCameraPackage;` to the imports at the top of the file
  - Add `new CBCapichiCameraPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-capichi-camera'
  	project(':react-native-capichi-camera').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-capichi-camera/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-capichi-camera')
  	```


## Usage
```javascript
import CBCapichiCamera from 'react-native-capichi-camera';

// TODO: What to do with the module?
CBCapichiCamera;
```

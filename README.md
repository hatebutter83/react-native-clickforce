<<<<<<< HEAD

# react-native-clickforce

## Getting started

`$ npm install react-native-clickforce --save`

### Mostly automatic installation

`$ react-native link react-native-clickforce`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-clickforce` and add `RNClickforce.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNClickforce.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNClickforcePackage;` to the imports at the top of the file
  - Add `new RNClickforcePackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-clickforce'
  	project(':react-native-clickforce').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-clickforce/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-clickforce')
  	```


## Usage
```javascript
import RNClickforce from 'react-native-clickforce';

// TODO: What to do with the module?
RNClickforce;
```
  
=======
# react-native-clickforce
React Native module for Clickforce SDK
>>>>>>> de9cc62d9e6f3cea6694df053075b17f770fc91c

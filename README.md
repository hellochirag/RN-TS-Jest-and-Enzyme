# RN + TS + Jest and Enzyme
Test-driven RN Development: RN + TS + Unit Testing with Enzyme and Jest

As of v0.18, React Native uses React as a dependency rather than a forked version of the library,
which means it is now possible to use enzyme's `shallow` with React Native components.

Unfortunately, React Native has many environmental dependencies that can be hard to simulate without
a host device.

This can be difficult when you want your test suite to run with typical Continuous Integration servers
such as Travis.

To use enzyme to test React Native, you currently need to configure an adapter, and load an emulated DOM.
## Screenshots


<p>
<img src="https://raw.githubusercontent.com/JadavChirag/RN-TS-Jest-and-Enzyme/master/SS/1.png" width = "400">
<img src="https://raw.githubusercontent.com/JadavChirag/RN-TS-Jest-and-Enzyme/master/SS/2.png" alt="upload photo example"width = "400" >
<img src="https://raw.githubusercontent.com/JadavChirag/RN-TS-Jest-and-Enzyme/master/SS/3.png" alt="go to a profile from feed" width = "400">
<img src="https://raw.githubusercontent.com/JadavChirag/RN-TS-Jest-and-Enzyme/master/SS/5.png" width = "400" >
  
</p>

## Prerequiestes
* Node v8.3+
* Npm v5.0+
* Watchman v4.0+
* Xcode v9.3+
* Android SDK
* Java Development Kit (v8 or newer)
* Enzyme 
* React 16.x
* Jest 24.x
* Enzyme 3.x
* Babel 7.x
* ESLint support

## Getting Started

You can download this repo or clone using below command. (folder-name will be project folder in which you want to start your project).
```
git clone <REPO URL> <folder-name>
```
or from **Download Zip**
```
<REPO URL>
```

## Installing Dependencies

Install it once globally:
```
> npm install -g react-native-cli   (install the React Native command line interface)
```
Now go to project folder and run this command:
```
> npm install     (this will install all node dependencies)
```

## Unit Testing Run
```
$ npm run test

```

## TDD Result 

```
Test Suites: 1 failed, 1 passed, 2 total
Tests:       5 failed, 1 passed, 6 total
Snapshots:   1 obsolete, 0 total
Time:        2.613s, estimated 3s

```


## Project Run

Now go to project folder and run this command:

### For iOS (Device or simulator)

```
> react-native run-ios
```

### For Android (Device or simulator)

```
> react-native run-android
```
>Everythig is setup and you are good to go now. Happy Coding :)

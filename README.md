# Introduction to Navigation in React Native
This is the initial setup to play around with different react native navigators such as stack navigator, tab navigator and drawer navigator

## System Requirements

- [React Native Development Setup](https://reactnative.dev/docs/environment-setup)
- [Android Studio latest](https://developer.android.com/studio) `^4.x`
- [Xcode](https://developer.apple.com/download/more/?=xcode) `^12.x.x`
- [git][https://git-scm.com/] `2.x`
- [NodeJS][https://nodejs.org] `12.15.0`
- [npm][https://www.npmjs.com/] `^6.x`
- [yarn][https://yarnpkg.com/getting-started/install]

### Note: 
- This project is not using **expo** to bootstrap the application, Just follow [**react-native cli quickstart**](https://reactnative.dev/docs/environment-setup)
- All of these must be available in your `PATH`. To verify things are set up
properly, you can run this:

```shell
git --version
node --version
npm --version
xcode-select --version
```

# To Run the Application

You can use yarn or npm to run the scripts

### Start Metro Server

```js
yarn start
```

### Start IOS App

```js
yarn ios
```

### Start Android App

```js
yarn android
```

## POD
***

#### Pod install
Run `pod install` in `/ios` subfolder of Project

```js
yarn pod
```

#### Pod update
> if more than one users are working on the project and they have different versions of pods in Podfile.lock you run `pod update` command to sync & install pods according to latest version


Run `pod update` in `/ios` subfolder of Project

```js
pod update
```

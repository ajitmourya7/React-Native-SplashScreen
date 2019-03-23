# React-Native-SplashScreen
Creating SplashScreen in React Native Using ReactNativeSplashScreeen Package and Android Studio

## Quick start

### Installation of React Native

```sh
npm install -g react-native-cli

```
install all react native prerequisites

in splashscreen folder open terminal

```sh
npm install

react-native start

```
and in same folder open another terminal to install in android phone 

```sh
react-native run-android device 

```
but it required your phone to be connected with your pc or laptop.

# To Add Splash Screen 

First take logo of @1x = 200px, @2x = 400px, @3x = 600px;

mipmap-mdpi = icon.png
mipmap-hdpi = icon@2x.png
mipmap-xhdpi = icon@3x.png
mipmap-xxhdpi = icon@3x.png

Add your Logo in Drawable and replace @mipmap/tooth with @mipmap/{with your logo name} using android studio.

```sh
npm install react-native-splash-screen@3.0.6 
react-native link
react-native run-android device 

```
and your splash screen is added.

# ScreenShot

### SplashScreen

<img src="https://user-images.githubusercontent.com/20237265/54864244-acaeda80-4d7a-11e9-8909-a036c1e30ec2.jpg" data-canonical-src="https://user-images.githubusercontent.com/20237265/54864244-acaeda80-4d7a-11e9-8909-a036c1e30ec2.jpg" width="200" height="400" />


### Home Page

<img src="https://user-images.githubusercontent.com/20237265/54864256-d49e3e00-4d7a-11e9-9564-2c6b287be86f.jpg" data-canonical-src="https://user-images.githubusercontent.com/20237265/54864256-d49e3e00-4d7a-11e9-9564-2c6b287be86f.jpg" width="200" height="400" />

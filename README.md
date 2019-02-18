# Learnt in 2019 - [GYMER]

This is the fourth app of the **Learnt in 2019** series. I always wanted a TABATA Timer kinda app, but a simplified one for my gym workouts. So, I thought why not build one, and experiment on the hybrid mobile app development.

**Gymer** is a mobile based timer app built using Ionic 4. With this, you can set timer for your gym workouts intervals and you can check the total time for the whole workout session.

![Initial State](./extras/1.jpg?raw=true "Initial State")
![Timer Started](./extras/2.jpg?raw=true "Timer Started")
![Timer Completed](./extras/3.jpg?raw=true "Timer Completed")

## Learnings

* Develped my first hybrid mobile app using [Ionic](https://ionicframework.com/)
* This project was generated with [Ionic CLI](https://ionicframework.com/getting-started#cli) version 4.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development.

### Prerequisites

Ionic shosuld be installed globally. ```npm install -g ionic```
[Android Studio](https://developer.android.com/studio/install.html) should be installed.

### Installing

1. Clone this repo to your local.
2. Do ```npm install``` inside the repo root folder.
3. Do ```ionic serve```. Navigate to ```http://localhost:8100``` in the browser and the app will be ready.

### Building the app
1. Do ```ionic cordova platform add android```
2. Do ```ionic cordova build android```. Once completed you can the apk file for android in an output folder. Install in your mobile and start working out

## TODO
* Audio, Voice based instructions
* Unit test cases

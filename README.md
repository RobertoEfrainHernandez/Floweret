# Floweret
Final App Project for Udacity Nanodegree Program

This app is called Floweret. The app allows a user to take photos of flowers and save them into their collection using Firebase Storage. Once it is in their album, the app will use a FlowerClassifier to recognize the flower in the photo and display it's Wikipedia image and flower name in the cell. When the user selects the cell, it will open into a WebViewController showing the Wikipedia information of the flower.

## Project Screenshot
![Screenshot](https://drive.google.com/open?id=1EkmWJfdI--X2AfL3oR-ejxPvI58aMIO8)

## Implemention
1. First Screen is the InitialHomeController in which you have the option to Login into the app or Register into the app.
2. Once authenticated you are first presented a TabBarController where the first Tab is a Camera Screen. This is where the User is allowed to make a photo selection via Camera or Photo Library of a Flower, and once selection is made, their photo is presented on screen. When that occurs, the Cancel button is enabled where the User can discard the image, or Save button is enabled to save their photo to their Flower collection.
3. Once saved to their collection, the User can see their photos in the Album Tab. But, when the images are loaded in the Collection tab, the User will see a Flower image and Flower Name provided by Information requested from Wikipedia.
4. If the User selects a Flower Image, they will be redirected to the Wikipedia page of the Flower to get more information.
5. Lastly, the User is allowed to Log Out from either Tab selection.

## How To Build
This project includes Cocoapods, so first you must go to the project directory in terminal and do pod install. Once you open the project's .xcworkspace you must hit Comman+B in order to build the project's pods.

## Requirements
- Xcode 9.4
- Swift 4.1

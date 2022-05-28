# Bionic Reader Safari Extension for macOS and iOS
Safari Extensnion to allow you to enable bionic reading on any website. 
Builds for both macOS and iOS.

For the meantime, this is only a macOS release. You can build for iOS but I cannot distribute outside of the App Store.

Will aim to have signed and published on the App Store soon, so that you can easily install on both iOS and macOS

Based on [ansh/bionic-reading](https://github.com/ansh/bionic-reading)

# Installation Instructions
- Download .zip file from Releases, and unzip
- Install .app file to your Applications folder
- Enable Developer Mode on Safari by going to Safari Preferences > Advanced > Enable Develop menu in menu bar
- Enable Unsigned Extensions by going to Develop > Enable Unsigned Extensions

You will have to open Bionic Reader once, and open it from the Security & Privacy menu in System Settings. 

# Build Instructions
- Clone repo using GitHub Desktop or xcode
- Make sure you have both a Team and a Signing Certificate set on each of the build targets
- Should build fine just as is, no other editing required.

If you want to build for iOS, make sure you have your iOS device connected and set as the build target.

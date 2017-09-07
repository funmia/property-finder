# property-finder

## setup

Install node.js
```
brew install node
```

Next, use homebrew to install watchman, a file watcher from Facebook:
```
brew install watchman
```
This is used by React Native to figure out when your code changes and rebuild accordingly. It’s like having Xcode do a build each time you save your file.

Then:
```
git clone git@github.com:funmia/property-finder.git
cd PropertyFinder
npm install
```
```
Open the PropertyFinder.xcodeproj in the ios folder with Xcode,
then build and run.
```
or
```
react-native run-ios
```

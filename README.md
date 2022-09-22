Ruby script for visualizing dependencies between elements in the Swift project based on doccarchive information.

About DocC: https://developer.apple.com/documentation/docc
OSS: https://github.com/apple/swift-docc

usage: Execute this script after generating the DocC documentation archive with xcodebuild command.

```sh
$ xcodebuild -workspace TARGET_NAME.xcworkspace -scheme TARGET_NAME -sdk iphonesimulator -destination 'platform=iOS Simulator,name=iPhone 13 Pro,OS=16.0'  docbuild -derivedDataPath .build
$ ./dependency TARGET_NAME
```
Also, an environment for using PlantUML is required.

https://plantuml.com/ja/starting

```sh
brew install graphviz
brew install plantuml
```

⚠️This is just a reference implementation.

Feel free to use it as a practical reference for your own projects, but I will not be maintaining this repository.

This is a demo application showing how to use the HockeySDK-tvOS SDK.

The SDK is integrated as a git submodule adding the HockeySDK-tvOS Xcode project as a subproject.

## Release Notes

Version 1.0:

- First public release

## Getting started

Get the code with HockeySDK-tvOS SDK submodule

`git clone --recurse-submodules https://github.com/bitstadium/HockeySDK-tvOSDemo.git`

Open HockeySDK-tvOSDemo.xcodeproj with Xcode IDE or from command line
```
cd HockeySDK-tvOSDemo
open HockeySDK-tvOSDemo.xcodeproj
```

Replace appId and secret from HockeyApp portal in `AppDelegate.swift`:
```
static var appId: String = "YourAppID"
static var secret: String = "YourSecretKey"
```

Build and run sample project.


## Code of Conduct

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Contributor License

You must sign a [Contributor License Agreement](https://cla.microsoft.com/) before submitting your pull request. To complete the Contributor License Agreement (CLA), you will need to submit a request via the [form](https://cla.microsoft.com/) and then electronically sign the CLA when you receive the email containing the link to the document. You need to sign the CLA only once to cover submission to any Microsoft OSS project. 

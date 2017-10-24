## Idea behind iOS Cosmos

Few months ago, a friend of mine asked me if there is a single place where he can find everything he needs to know about iOS development. He was looking for something that will help him get started not only with iOS development APIs or frameworks but also find out what it takes to build a complete product. 

He was interested to find out what are our choice of tools for Continuous Integration and what do we use to distribute our apps to beta testers, what are the security guidelines the community recommends. 

Having worked as an iOS developer for several years I knew there isn't any such site or resource. The resources are often distributed accross official Apple documentation, tons of tutorial sites, blogs, podcasts, books, newsletters, tweets from renowned iOS developers and what not. 

And there is also [awesome-ios](https://github.com/vsouza/awesome-ios) by [Vinicius Souza](https://github.com/vsouza). So I don't want to recreate it. 

However, I definitely see something is missing in all of the above resources. A community driven single point reference. I hope **iOS Cosmos** helps to solve this.

* [Getting started with Xcode](#xcode)
* [Language used for iOS development](#languages)
* [Dependency Manager](#dependency_manager)
* [iOS Architecture & Design Patterns](#arch_patterns)
* [Building UI](#building_ui)
* [Writing Tests](#tests)
	- [Unit Tests](#unit_tests)
	- [UI Tests](#ui_tests)
	- [Device Farm](#device_farm)
* [Crash Analytics](#crash_analytics)
* [Usage Analytics](#usage_analytics)
* [Continuous Integration Tools](#ci)
* [Continuous Deployment and Beta Testing](#cd)
* [A/B Testing](#ab_testing)
* [Code Quality & Standards](#code_quality)
* [Automated Security Scanning](#security)
* [Performance / Memory Testing](#performance)
* [Localization (l10n) / Internationalization (i18n)](#i18n)
* [Accessibility](#accessibility)
* [Mobile Device Management (MDM)](#mdm)
* [Building Enterprise Apps](#enterprise)

### Getting started with Xcode<a name="xcode"></a>

- [Xcode](https://developer.apple.com/xcode/)

### Language used for iOS development<a name="languages"></a>

- [Swift](https://developer.apple.com/swift/)
- [Objective-C](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html)

### Dependency Manager<a name="dependency_manager"></a>

- [Cocoapods](https://cocoapods.org)
- [Carthage](https://github.com/Carthage/Carthage)

### iOS Architecture & Design Patterns<a name="arch_patterns"></a>

* [iOS Architecture Patterns](https://medium.com/ios-os-x-development/ios-architecture-patterns-ecba4c38de52)
* [Model-View-Controller](https://developer.apple.com/library/content/documentation/General/Conceptual/DevPedia-CocoaCore/MVC.html)
* [Model-View-ViewModel](https://www.objc.io/issues/13-architecture/mvvm/)
* [Flux](http://blog.benjamin-encz.de/post/real-world-flux-ios/)
* [Viper](https://www.objc.io/issues/13-architecture/viper/)
* [Model-View-Presenter](https://www.smashingmagazine.com/2016/05/better-architecture-for-ios-apps-model-view-controller-pattern/)
* [iOS Design Patterns - Course](https://www.raywenderlich.com/164993/new-course-ios-design-patterns)

### Building UI<a name="building_ui"></a>

- [Storyboard](https://developer.apple.com/library/content/documentation/General/Conceptual/Devpedia-CocoaApp/Storyboard.html)
- [Interface Builder](https://developer.apple.com/xcode/interface-builder/)
- [Auto Layout](https://developer.apple.com/library/content/documentation/UserExperience/Conceptual/AutolayoutPG/index.html)
- [iOS Human Interface Guidelines](https://developer.apple.com/ios/human-interface-guidelines/)

### Writing Tests<a name="tests"></a>

- [Testing with Xcode](https://developer.apple.com/library/content/documentation/DeveloperTools/Conceptual/testing_with_xcode/chapters/01-introduction.html)

**Unit Tests**<a name="unit_tests"></a>

- [Quick](https://github.com/Quick/Quick)
- [Nimble](https://github.com/Quick/Nimble)
- [XCTest](https://developer.apple.com/documentation/xctest)
- [Test coverage reports using Slather](https://github.com/SlatherOrg/slather)

**UI Tests**<a name="ui_tests"></a>

- [UI Testing with XCUITest](https://developer.apple.com/library/content/documentation/DeveloperTools/Conceptual/testing_with_xcode/chapters/09-ui_testing.html)
- [Calabash](http://calaba.sh)
- [Testing with Frank](http://testingwithfrank.github.io)

**Device Farm**<a name="device_farm"></a>
- [AWS Device Farm](https://aws.amazon.com/device-farm/)
- [Xamarin Test Cloud](https://www.xamarin.com/test-cloud)

### Crash Analytics<a name="crash_analytics"></a>

- [Fabric Crashlytics](https://fabric.io/kits/ios/crashlytics)
- [Sentry](https://sentry.io)

### Usage Analytics<a name="usage_analytics"></a>

- [Answers by Fabric](https://fabric.io/kits/ios/answers)
- [Google Analytics](https://developers.google.com/analytics/devguides/collection/firebase/ios/)
- [Flurry iOS SDK](https://github.com/flurry/flurry-ios-sdk)

### Continuous Integration Tools<a name="ci"></a>

- [Continuous Integration with Xcode](https://developer.apple.com/library/content/documentation/IDEs/Conceptual/xcode_guide-continuous_integration/)
- [Fastlane](https://fastlane.tools)
- [Jenkins](https://jenkins.io/doc/)
- [Travis](https://travis-ci.com)
- [Bitrise](https://www.bitrise.io)

### Continuous Deployment and Beta Testing<a name="cd"></a>

- [Test Flight](https://developer.apple.com/testflight/)
- [HockeyApp](https://hockeyapp.net)
- [applivery](http://applivery.com)

### A/B Testing<a name="ab_testing"></a>

- [Optimizely](https://www.optimizely.com)
- [Firebase Remote Config](https://firebase.google.com/docs/remote-config/)
- [Taplytics](https://taplytics.com/mobile-ab-testing/)

### Code Quality & Standards<a name="code_quality"></a>

- [Swiftlint](https://github.com/realm/SwiftLint)
- [Sonarqube](https://www.sonarqube.org)
- [Danger](https://github.com/danger/danger)

### Automated Security Scanning<a name="security"></a>

- [AppKnox](https://www.appknox.com)
- [Data Theorem](https://www.datatheorem.com)
- [AppWatch](http://appwatch.io)

### Performance / Memory Testing<a name="performance"></a>

- [Xcode Instruments](https://developer.apple.com/library/content/documentation/DeveloperTools/Conceptual/InstrumentsUserGuide/index.html)
- [FBMemoryProfiler](https://github.com/facebook/FBMemoryProfiler)

### Localization (l10n) / Internationalization (i18n)<a name="i18n"></a>

- [Internationalization](https://developer.apple.com/library/content/documentation/MacOSX/Conceptual/BPInternational/Introduction/Introduction.html)
- [Data Formatting Guide](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/DataFormatting/DataFormatting.html)

### Accessibility<a name="accessibility"></a>

- [Supporting Accessibility](https://developer.apple.com/library/content/featuredarticles/ViewControllerPGforiPhoneOS/SupportingAccessibility.html)
- [Testing Accessibility](https://developer.apple.com/library/content/technotes/TestingAccessibilityOfiOSApps/TestingtheAccessibilityofiOSApps/TestingtheAccessibilityofiOSApps.html)
- [Accessibility on iOS](https://developer.apple.com/accessibility/ios/) 

### Mobile Device Management (MDM)<a name="mdm"></a>

- [Jamf](https://www.jamf.com/solutions/)
- [Apple Deployment Program](https://deploy.apple.com)
- [MobileIron](https://www.mobileiron.com)

### Building Enterprise Apps<a name="enterprise"></a>

- [SAP Mobile Platform](https://www.sap.com/sea/products/mobile-app-development-platform.html)
- [IBM Worklight](https://www.ibm.com/support/knowledgecenter/en/SSZH4A_6.0.0/com.ibm.worklight.getstart.doc/topics/c_overview.html)
- [SAP Fiori](https://www.sap.com/sea/products/fiori.html)
- [SAP UI5](https://sapui5.hana.ondemand.com)

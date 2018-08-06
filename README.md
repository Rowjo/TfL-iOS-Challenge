# TfL iOS Coding Challenge

This project uses Swift 4 and Alamofire / SwiftyJSON for networking and serialisation.

## Build Project
[Cocoapods](https://cocoapods.org/) is used for depencency management. To install dependencies first install Cocoapods, then:
    
    pod install

Open `TflChallenge.xcworkspace` which includes a target for dependencies.
    
## Run Tests

Tests are written using XCTest. Run in Xcode by selecting Product -> Test. 

## Comments

* The Road endpoint (api.tfl.gov.uk/Road) operates without providing url parameters for Application key or Application ID
* As the full list of road statuses is not provided by the API, no enums are used and these are serialised as Strings rather
* It has been assumed that the api is provides no search facility and road names must be matched exactly


> Note: Enter a valid Application ID and Application Key in `Constants.swift` which can be found in the [Tfl API Portal](https://api-portal.tfl.gov.uk).





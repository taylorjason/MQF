# MQF
![Current status of UI and Unit Tests workflow](https://github.com/airmencoders/MQF/workflows/UIandUnitTests/badge.svg)

This project is an app to help US Air Force Airmen study their Master Question File tests. It is Built by Airmen for Airmen as part of the [Airmen Coders](https://airmencoders.us) project.




Please read the INTENT.md file and the LICENSE.md file for information on using this code in your own projects.

We would love to have you join the team, please submit an issue or PR with your suggestions. 



## How to run the code locally
1. Requires [XCode](https://developer.apple.com/xcode/) (from Apple) and [Cocoapods](https://cocoapods.org).
1. Download or Clone the project
1. Run pod install
1. Open MQF.xcworkspace
1. Click Run


## A note on our CI/CD pipeline
Because this is a static iOS app the continuous delivery portion of the pipeline does not exist. However, we test each commit using GitHub Actions and XCode’s Unit and UI Tests. A branch must pass the tests before it will be merged into Master.


## Libraries we use
* [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON) - MIT License
* [Eureka Forms](https://eurekacommunity.github.io) - MIT License
* [UICircularProgressRing](https://github.com/luispadron/UICircularProgressRing) - MIT License
* [QuizKit](https://github.com/steve228uk/QuizKit) - MIT License



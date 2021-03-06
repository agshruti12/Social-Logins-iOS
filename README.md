# Social Logins iOS
Basic app to show how to login with Facebook, Google, Twitter. Created for learning purpose :) using Xcode 9 and Swift 4.0

**Note:** Before running app please make sure -
1. run <br>
`cd Social logins iOS` <br>
`pod install`
2. Replace `Google Client ID` in [Constants.swift](https://github.com/imjog/Social-Logins-iOS/blob/master/Social%20Logins%20iOS/Constants.swift) file with your Google Client ID. To get Google Client ID and some other required resources please [follow this guide](https://developers.google.com/identity/sign-in/ios/start-integrating). 
3. Replace [GoogleService-Info.plist](https://github.com/imjog/Social-Logins-iOS/blob/master/Social%20Logins%20iOS/GoogleService-Info.plist) with your new **GoogleService-Info.plist** as mentioned in [this guide](https://developers.google.com/identity/sign-in/ios/start-integrating).
4. Replace `Twitter Consumer Key` and `Twitter Consumer Secret` in [Constants.swift](https://github.com/imjog/Social-Logins-iOS/blob/master/Social%20Logins%20iOS/Constants.swift) file with your Twitter App Consumer Keys. To get Consumer Key and Consumer Secret please [follow this guide](https://dev.twitter.com/twitterkit/ios/installation).
5. Replace **Info.plist** facebook and twitter keys with your keys. Find [facebook info.plist code here](https://developers.facebook.com/docs/facebook-login/ios#4--configure-your-info-plist) and Find Twitter info.plist code [here](https://dev.twitter.com/twitterkit/ios/installation).
6. Update URL Schemes: go to **TARGET > Info > URL Types** and replace your schems.
![Social Login](https://github.com/imjog/Social-Logins-iOS/blob/master/Social%20Logins%20iOS/Screenshots/Screen%20Shot%202018-01-17%20at%2015.27.04.png)

### How to use SDKs
* For facebook login, follow: [facebook swift sdk](https://github.com/facebook/facebook-sdk-swift)
* For twitter login, follow: [Twitter Kit iOS](https://github.com/twitter/twitter-kit-ios)
* For google login, follow: [Tri Sign-In for iOS](https://developers.google.com/identity/sign-in/ios/start)

### Contact
* Email: jogendra.iitbhu@gmail.com
* [LinkedIn](https://www.linkedin.com/in/jogendrasingh24/)
* [Twitter](https://twitter.com/imjog24)
* [Quora](https://www.quora.com/profile/Jogendra-Singh-63)
* [Facebook](https://facebook.com/jogendra.singh24)

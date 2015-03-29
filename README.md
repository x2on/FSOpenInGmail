# FSOpenInGmail [![Build Status](https://travis-ci.org/x2on/FSOpenInGmail.png)](https://travis-ci.org/x2on/FSOpenInGmail) [![Cocoa Pod](https://cocoapod-badges.herokuapp.com/p/FSOpenInGmail/badge.svg)](http://cocoadocs.org/docsets/FSOpenInGmail/) [![Cocoa Pod](https://cocoapod-badges.herokuapp.com/v/FSOpenInGmail/badge.svg)](http://cocoadocs.org/docsets/FSOpenInGmail/) [![License](https://go-shields.herokuapp.com/license-MIT-blue.png)](http://opensource.org/licenses/MIT)

FSOpenInGmail is a tool for sending mails with Gmail iOS App.

## Install
Using [CocoaPods](http://cocoapods.org/):

`pod 'FSOpenInGmail', '~> 1.0'`

## Usage

Check if Gmail app is installed: 

```objc
if ([FSOpenInGmail canSendGmail]) {
	//Gmail app is installed
}
```

Open Gmail app composer:
```objc
[FSOpenInGmail sendEmailTo:@"test@example.com" subject:@"Some subject" body:@"Some body"];
```

## System support
iOS 6.0+ is currently supported.

## License

FSOpenInGmail is available under the MIT license. See the LICENSE file for more info.

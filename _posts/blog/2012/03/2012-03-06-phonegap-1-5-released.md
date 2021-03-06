---
title: PhoneGap 1.5 Released!
date: 2012-03-06 01:02:59 Z
categories:
- app
tags:
- Release
author: Steve Gill
status: publish
type: post
format: html
---

The PhoneGap Community has done it again. We are happy to announce the release of [PhoneGap 1.5](http://phonegap.com/download)! This release contains many bug fixes from version 1.4.1.

Check out the release notes below to see all of the enhancements and fixes.

## Android

* CB-75 contact.remove does not remove the contact fully
* Missing first line of license in header.
* Add cordova.android.js from common-js build.
* Update build to use new common cordova.android.js instead of building js from multiple Android js files.
* Call js code using new common js way.
* Arguments are passed as JSON array, not JSON object.
* Add cordova.android.js from common-js build.
* Update build to use new common cordova.android.js instead of building js from multiple Android js files.
* File APIs should return error code instead of object.
* Updating cordova.android.js with File API fixes.
* Fix WebSQL for Android 4.0.2.
* Adding unsupported action plugin result return if invalid action string is specified to accel and compass listener plugins
* woops java type checks! love it!
* changing JS invoked from native to work with modular js
* Changed JavaScript invoked from PluginResult native code to use new modular JS approach
* Unifying File API error code/response style
* removing unnecessary try/catch
* Return string for root location in requestFileSystem
* Prefix URIs for file API with file:/// and persistent storage should never point to SD card
* Need to add/trim file:// where applicable
* truncating file:// protocol where applicable in metadata func
* remove file:// protocol from various fileutils remove methods
* remove file:// protocol from various fileutils* methods
* remove trailing slash
* Use strings not objects
* trim file:// URI from uri-&gt;path conversion method
* more file:// URI truncation :D
* Adding unsupported action plugin result return if invalid action string is specified to accel and compass listener plugins
* woops java type checks! love it!
* changing JS invoked from native to work with modular js
* Changed JavaScript invoked from PluginResult native code to use new modular JS approach
* Unifying File API error code/response style
* removing unnecessary try/catch
* Return string for root location in requestFileSystem
* Prefix URIs for file API with file:/// and persistent storage should never point to SD card
* Need to add/trim file:// where applicable
* truncating file:// protocol where applicable in metadata func
* remove file:// protocol from various fileutils remove methods
* remove file:// protocol from various fileutils* methods
* remove trailing slash
* Use strings not objects
* trim file:// URI from uri-&gt;path conversion method
* more file:// URI truncation :D
* updating cordova.android.js. This resolves CB-283: unregistration of backbutton event handlers do not fire appropriate native method
* updating cordova.js to include camera constants fix. added clean dependency to build-javascript target in ant file
* Switching headers.* Got OK months ago from Simon and Bryce on re-write. No Android Demo code in current project
* Changing to CordovaInterface in preparation of CordovaWebView
* Change related to FileTransfer, need to get a test going for this somehow
* Adding custom headers to upload
* Moved the CordovaInterface over to master, doing this before working on CordovaJS
* Fix to CordovaInterface methods, DroidGap has the managedQuery since it inherits from Activity. (CB-282)
* Reverting interface change, not enough time for testing, need to remove it manually
* Putting back the CordovaInterface work after talking with Simon
* Updating the JS, even though it shouldn't be here. CB-290
* Rename to Cordova
* Fixing MediaFileData problem for MP4 video types
* Adding com.phonegap.api stubs for legacy user created plugins
* Refactor out the Java casting code
* Redirect Issue
* Fix issue with document.location.href not calling loadUrlIntoView
* Removing extraneous logging from DroidGap.java left over from rebase
* Refactoring the checks for file:// into a convenience method
* CB-3: Apache source headers in callback-android
* Fixing app crash when clicking Menu or Back buttons while splashscreen is being shown.
* Tagging 1.5.0rc1
* Adding startActivity method to CordovaInterface as many plugins rely on this method
* Fixing the call to Media.onStatus()
* Switching to require syntax for AudioPlayer
* Revert change in location of FileSystem
* Updating cordova.android.js to latest version from Apache git repo
* Updating cordova.android.js to override FileReader
* Tagging 1.5.0
* Adding support for legacy plugins

## Blackberry

* CB-5: Switching license to Apache license.
* CB-226 Rename to Cordova.
* Delete plugin template.
* Properly recognize when alternate simulator path specified.
* Add Entry.toURL, deprecate Entry.toURI.
* 1.5.0

## iOS

* Fixed memory allocation warnings from analyzer
* Updates for 1.5.0rc1
* Update FileEntry and DirectoryEntry to deprecate toURI() and add toURL
* Fix NSLog crash in CDVWhitelist.m - parameter order reversed
* Update to version 1.5
* added german/swedish localization for fix #162
* Change Reachability to PGReachability to avoid clashes with other libs
* Updated the Upgrade Guide for 1.4.1
* Added UIWebViewBounce key to PhoneGap.plist (default is YES) (originally from an @alunny pull request)
* Updated README.md FAQ item #5 (upgrades)
* Added the German and Swedish resources to the Xcode templates
* Fixes CB-149 - Black Bar visible after landscape video
* Fixes CB-221 - On an orientation change, the orientationchange event not fired on iOS 3 and 4 (it is however fired on iOS 5)
* Rename PhoneGap to Cordova.
* Fixed typo, added missing step.
* Cordova rename fixes.
* Completed Cordova Guides for 1.5.0
* Fixed CB-253 - Xcode 4 Cordova-based Application - DEBUG macro not defined
* Default GCC_VERSION is com.apple.compilers.llvm.clang.1_0 now
* Removed Xcode and iOS SDK checks in the installer (for Xcode 4.3 installs which go under /Applications now

## Windows Phone

* Fixed WrappedXHR with headers
* stage 1 - bulk rename
* stage 2 - fix errors
* Moar renames
* Fix issue with single call to get heading from Compass API
* almost there
* fix for setRequestHeader
* Bunch more renaming
* removed stuff
* image updates
* renamed project refs
* fixed test project
* updated links to older phonegap.js files
* Updating templates
* add images
* new template
* MimeTypeMapper is required
* custom template
* removed bunk
* save me re-thinking what the description should be everytime. Note, this should be an automated process ...
* updated template for bare-bones apps
* one more thing ...
* oops
* skip having to rename all the files
* update 1.4.1 references to 1.5.0
* added templates for 1.5 quick dev, updated VERSION
* template descriptions can only be one line... awesome
* update instructions
* simplified, renamed Gap-&gt;Cordova
* Removed non-sense

## Bada

* CB-219 Rename PhoneGap to Cordova

If you wish to follow or join in the development of this project, send an email to <a href="mailto:callback-dev-subscribe@incubator.apache.org">callback-dev-subscribe@incubator.apache.org</a> to subscribe to the developer mailing list.

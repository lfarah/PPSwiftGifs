[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)

# PPSwiftGifs

PPSwiftGifs provides a convenient way to show animated GIF images as a part of iOS GUI.

## Installation

#### Carthage
Create a `Cartfile` that lists the framework and run `carthage bootstrap`. Follow the [instructions](https://github.com/Carthage/Carthage#if-youre-building-for-ios) to add `$(SRCROOT)/Carthage/Build/iOS/PPSwiftGifs.framework` to an iOS project.

```
github "peterprokop/PPSwiftGifs"
```
#### Manually

* Just clone this repo and add ```PPSwiftGifs.swift``` to your project.
* Add ImageIO.framework to your project.
* Add ```#import <ImageIO/ImageIO.h>``` to bridging header.

## Requirements

Swift 2.0:
Use [swift-2.0 branch](https://github.com/peterprokop/PPSwiftGifs/tree/swift-2.0)
- iOS 7.0+ (iOS 8.0+ if you use Carthage)
- Xcode 7.0+

Swift 1.2:
- iOS 7.0+ (iOS 8.0+ if you use Carthage)
- Xcode 6.3+

Swift 1.1:
Use [swift-1.1 branch](https://github.com/peterprokop/PPSwiftGifs/tree/swift-1.1)
- iOS 7.0+
- Xcode 6.1-6.2

## Usage

```
imageView.image = PPSwiftGifs.animatedImageWithGIFNamed("gif_name")
```

(File named "gif_name.gif" should be present in your project and copied as a bundle resource.
As far as I know, you can't add GIFs to asset catalogs.)

## Author(s)

PPSwiftGifs is written by Peter Prokop but borrows heavily from 
[uiimage-from-animated-gif](https://github.com/mayoff/uiimage-from-animated-gif)
project by Rob Mayoff.

## Contribution

You are welcome to fork and submit pull requests

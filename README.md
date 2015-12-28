# CShapelib
Module map to use [shapelib](http://shapelib.maptools.org) with [Swift's package manager](https://github.com/apple/swift-package-manager/blob/master/Documentation/SystemModules.md)

## Example

```Swift
import PackageDescription

let package = Package(
    dependencies: [
      .Package(url: "https://github.com/choefele/CShapelib.git", majorVersion: 1)
    ]
)
```

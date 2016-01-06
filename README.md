# CJSONC
Swift C module for json-c (Linux)

For details about using json-c, see the official repository at https://github.com/json-c/json-c

## Including in Swift Code

Add a ```.Package``` dependency to your ```Package.swift``` file as shown in the following example:

```
import PackageDescription

let package = Package(
  name:  "translator",
  dependencies: [
    .Package(url:  "https://github.com/iachievedit/CJSONC", majorVersion: 1),
    .Package(url:  "https://github.com/PureSwift/CcURL", majorVersion: 1)
  ]
)
```

## Ubuntu Installation

Install the development headers for libjson-c:

```sudo apt-get install -y libjson-c-dev```


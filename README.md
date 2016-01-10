# CNCURSES
Swift C module for ncurses (Linux)

For details about using ncurses, see http://invisible-island.net/ncurses/.

## Including in Swift Code

Add a ```.Package``` dependency to your ```Package.swift``` file as shown in the following example:

```
import PackageDescription

let package = Package(
  name:  "myapp
  dependencies: [
    .Package(url:  "https://github.com/iachievedit/CNCURSES", majorVersion:1)
  ]
)
```

## Ubuntu Installation (Trusty)

Install the development headers for `libncurses5`:

```sudo apt-get install -y libncurses5-dev```


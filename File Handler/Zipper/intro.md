# v1.0.0
## added
1. can zip file.

Given 

+ path of files (can be represented as list of string or a string joined by comma), said `<sourceFiles>`
+ path of a folder that will zipped to, said `<destinationDirectory>`
+ file extension for zip, said `<zipFileExtension>`
+ file name for zip, said `<zipFileNameWithoutExtension>`.

It will zip these files `<sourceFiles>` to `<destinationDirectory>` and named to `<zipFileName>`

where

`<zipFileName>` is joined by `<zipFileNameWithoutExtension>` and `<zipFileExtension>`.

> [!WARNING]
> **DO NOT** leave any extra whitespace, tab or new line in path.

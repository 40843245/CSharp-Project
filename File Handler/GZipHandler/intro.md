# v1.0.0
## added
1. can compress file.
2. can set password.

Given 

+ path of files (can be represented as list of string or a string joined by comma), said `<sourceFiles>`
+ path of a folder that will zipped to, said `<destinationDirectory>`
+ file extension for zip, said `<zipFileExtension>`
+ file name for zip, said `<zipFileNameWithoutExtension>`.
+ password (used when decompressing), said `<password>`.

It will zip these files `<sourceFiles>` to `<destinationDirectory>` 

and named to `<zipFileName>` 

and set its password to `<password>` iff `<password>` is not null or empty string. 

When `<password>` is set, once one try to decompress the zip file, 

then it will pop up a dialog to enter password.

<img width="309" alt="image" src="https://github.com/user-attachments/assets/9161c5de-92ab-4548-aca5-458867c8987a" />

If your password matches `<password>`, then it will decompress the zip file.

Otherwise, it will not.


`<zipFileName>` is joined by `<zipFileNameWithoutExtension>` and `<zipFileExtension>`.

> [!WARNING]
> **DO NOT** leave any extra whitespace, tab or new line in path.

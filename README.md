FlatButton
==================
Layer based `NSButton` with Interface Builder styling options.

This is a subclass that lets you create beautiful `NSButton` controls easily.

<img src="https://s3.amazonaws.com/cindori/images/flatbutton.png" width="460">

## Installation (CocoaPods)
Configure your Podfile to use `FlatButton`:

```pod 'FlatButton'```

If you are using Swift 3:

```pod 'FlatButton', :git => 'https://github.com/OskarGroth/FlatButton.git', :branch => "swift3"```

If Xcode prompts you to convert project to Swift 3, you can choose Later and then edit the Pods xcodeproject build setting:
`Use Legacy Swift Language Version` to `No`.



## Usage

Create an `NSButton` in Interface Builder and set it's class to `FlatButton`.

You can now style your button from the inspector:

<img src="https://s3.amazonaws.com/cindori/images/inspector.png" width="320">

The same values can be accessed from your code.

## License
The MIT License (MIT)

Copyright (c) 2016 Oskar Groth

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

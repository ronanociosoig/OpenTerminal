# OpenTerminal
---

## What is this?

A very simple plug-in for XCode that adds a short cut menu option to the File menu which opens a new terminal window in the current project.

## How to use it?

Build the OpenTerminal target in the Xcode project and the plug-in will automatically be installed in `~/Library/Application Support/Developer/Shared/Xcode/Plug-ins`. Relaunch Xcode and it will add the new menu item in the File menu.

## Background

The code packages an existing AppleScript that is called when the menu option is selected. 

## Notes

This project is compiled with garbage collection supported, and ARC disabled.

Compatible with XCode 4 and 5.

## License

MIT License

    Copyright (c) 2013 Mobile Genius LLC.
    
    Permission is hereby granted, free of charge, to any person obtaining a copy of
    this software and associated documentation files (the "Software"), to deal in
    the Software without restriction, including without limitation the rights to use,
    copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the
    Software, and to permit persons to whom the Software is furnished to do so,
    subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
    FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
    COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
    IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
    CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

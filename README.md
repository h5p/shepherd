Shepherd
======

Shepherd is a javascript library for guiding users through your app. It uses Tether, another open source library, to position all of its steps.

## Usage

Shepherd is wrapped to be compatible with H5P. This means it is available using H5P.Shepherd.
```
npm install
npm run build
```
Run in git bash on Windows.

## Changes

Changes have been made. See the `update_css.patch` diff file.  
Build flow applies patch automatically provided that `patch` command is available.  
`shepherd` v1.1.1 dependency cloned as git repository because it requires deprecated python 2. (build fails on python 3)

## License

Copyright (c) 2015 HubSpot, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

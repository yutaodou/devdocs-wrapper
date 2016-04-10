# DevDocs Wrapper

A simple wrapper for [DevDosc](http://devdocs.io) with [Electron](https://github.com/atom/electron) for desktop application like user experience.

## Package
### Create a package for Mac OSX:

```
npm install electron-packager -g
electron-packager . DevDocs --platform=darwin --arch=x64 --icon=icon.icns
```
### Create a package for Windows:

#### x64

```
npm install electron-packager -g
electron-packager . DevDocs --platform=win32 --arch=x64 --icon=icon.icns
```

#### x86

```
npm install electron-packager -g
electron-packager . DevDocs --platform=win32 --arch=ia32 --icon=icon.icns
```

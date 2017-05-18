# electron-deep-linking-osx


Open app and pass parameters with Deep-Linking using Electron (OSX).

![](https://github.com/oikonomopo/electron-deep-linking-osx/blob/master/electron-deeplinking-osx-example.gif)

This app is registered as ```myapp://```. For example, open Safari browser, enter ```myapp://param``` at address bar. Then 'electron-deep-linking-osx' app will start!

This is based on the [Quick Start Guide](http://electron.atom.io/docs/tutorial/quick-start) within the Electron documentation, then followed [‘electron-builder’ quick-setup-guide](https://github.com/electron-userland/electron-builder#quick-setup-guide) to produce mac installer

## Issue

In first instance, app shows dialog with url but can't log it to dev console. If app is opened already, every url is shown both at dialog module and at dev console! 

// TODO Investigate

## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/oikonomopo/electron-deep-linking-osx.git
# Go into the repository
cd electron-deep-linking-osx
# Install dependencies
npm install
# Run the app
npm start
# Produce installer
npm run dist
```
After running the installer (electron-deep-linking-osx/dist/electron-quick-start-1.0.0.dmg), you can try to open myApp with Deep-Linking, entering myapp://param at Safari address-bar.

## License

[GNU GPLv3](LICENSE.md)

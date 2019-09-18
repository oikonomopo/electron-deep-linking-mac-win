# electron-deep-linking-macOS-win32
[![codebeat badge](https://codebeat.co/badges/62d56692-2100-4dee-ad02-80fdb2fd3838)](https://codebeat.co/projects/github-com-oikonomopo-electron-deep-linking-mac-win-master)


Open app and pass parameters with deep linking using Electron (macOS/win32).

This app is registered as ```myapp://```. For example, open Safari browser, enter ```myapp://param``` at address bar. Then 'electron-deep-linking-mac-win' app will start and provided url will be printed to dev console!


![](https://github.com/oikonomopo/electron-deep-linking-osx/blob/master/electron-deeplinking-osx-example.gif)


Project is based to [Quick Start Guide](http://electron.atom.io/docs/tutorial/quick-start) within the Electron documentation, then followed [‘electron-builder’ quick-setup-guide](https://github.com/electron-userland/electron-builder#quick-setup-guide) to produce macOS/win32 installers.

## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/oikonomopo/electron-deep-linking-mac-win.git
# Go into the repository
cd electron-deep-linking-mac-win
# Install dependencies
npm install
# Run the app
npm start
# Produce installer
npm run dist
```
After running the installer (at electron-deep-linking-mac-win/dist/), you can try to open 'electron-deep-linking-mac-win' app with deep linking, by entering ```myapp://param``` at Safari address-bar. At chrome it will work by embedding the custom url in a link: f.e. <a href="myapp://param">Open app</a>

## License

[GNU GPLv3](LICENSE.md)

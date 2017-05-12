# electron-deep-linking-osx


Open app and pass parameters with Deep-Linking using Electron (OSX).

![](https://github.com/oikonomopo/electron-deep-linking-osx/blob/master/electron-deeplinking-osx-example.gif)

This app is registered as ```myapp://```.

For example, open Safari browser, enter ```myapp://param``` at address bar. Then 'electron-deep-linking-osx' app will start!

*In first instance app can't read custom url protocol. If app is opened already, every custom url protocol is passed!


This is based on the [Quick Start Guide](http://electron.atom.io/docs/tutorial/quick-start) within the Electron documentation, then followed [‘electron-builder’ quick-setup-guide](https://github.com/electron-userland/electron-builder#quick-setup-guide) to produce mac installer


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

If app is opened, it activates and you can see at dev tools console the log open-url event: ```myapp://param```!

// TODO When app is closed and have a call with custom-url-protocol, open app and get the custom-url-protocol!

## Resources for Further investigation

- [http://stackoverflow.com/questions/43912119/open-app-and-pass-parameters-with-deep-linking-using-electron-osx)
- [http://discuss.atom.io/t/custom-protocol-and-closed-app/37030)
- [http://github.com/masahirompp/electron-open-url-sample)
- [http://github.com/electron/electron/issues/3847)


## License

[GNU GPLv3](LICENSE.md)

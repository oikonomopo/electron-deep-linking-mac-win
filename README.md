# electron-deep-linking-osx

**Clone and run for a quick way to see electron-deep-linking-osx in action.**

Open app and pass parameters with Deep-Linking using Electron (OSX)
This is based on the [Quick Start Guide](http://electron.atom.io/docs/tutorial/quick-start) within the Electron documentation.

A basic Electron application needs just these files:

- `package.json` - Points to the app's main file and lists its details and dependencies.
- `main.js` - Starts the app and creates a browser window to render HTML. This is the app's **main process**.
- `index.html` - A web page to render. This is the app's **renderer process**.


## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/oikonomopo/electron-deep-linking-osx.git
# Go into the repository
cd electron-quick-start
# Install dependencies
npm install
# Run the app
npm start
# Produce installer
npm run dist
```
After running the installer (myApp/dist/electron-quick-start-1.0.0.dmg), you can try to open myApp with Deep-Linking, entering myapp://param at Safari address-bar.

If app is opened, it activates and you can see the log open-url event: myapp://param!

// TODO
If app is closed, it opens, but doesn't log anything!

## Resources for Further investigation

- [http://stackoverflow.com/questions/43912119/open-app-and-pass-parameters-with-deep-linking-using-electron-osx)
- [discuss.atom.io/t/custom-protocol-and-closed-app/37030)
- [github.com/masahirompp/electron-open-url-sample)
- [github.com/electron/electron/issues/3847)


## License

[CC0 1.0 (Public Domain)](LICENSE.md)

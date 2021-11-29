# SimpleCalculator

This is a basic web calcultor that uses a semi mvc set up.

all audio used was found online with a licence of open source.

**Clone and run for a quick way to see Electron in action.**

Here are some imporant files/folders to take note of in this Electron application:

- `package.json` - Points to the app's main file and lists its details and dependencies.
- `main.js` - Starts the app and creates a browser window to render HTML. This is the app's **main process**.
- `index.html` - Is the main view. **renderer process**.
- `/front-end` - all the assets such as the styling, controller, model, etc.

You can learn more about Electron from the [Quick Start Guide](https://electronjs.org/docs/latest/tutorial/quick-start).

## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/chulack/SimpleCalculator
# Go into the repository
cd SimpleCalculator
# Install dependencies
npm install
# Run the app
npm start
```

Note: If you're using Linux Bash for Windows, [see this guide](https://www.howtogeek.com/261575/how-to-run-graphical-linux-desktop-applications-from-windows-10s-bash-shell/) or use `node` from the command prompt.

## License

[MIT (Open Source)](LICENSE)

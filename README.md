# webpack-configuration

A collection of different Webpack setups for quick referencing or starting from.


## Start using for a new project, or playground

1. Clone the repo
2. Select the branch you want
3. Run `npm i` to install dependencies
4. Run one of the following commands, depending on intent:

### Production Build

```bash
npm run build
```

### Development Build

```bash
npm run build-dev
```

### Development Build, watching for file changes

```bash
npm run watch
```

### Development Server on port :8080

```bash
npm start
```

## See output without browser

After running a build command, you can see the output without opening a browser by running:

```bash
dist/main.js
```

### CSS Loader 

```bash
npm install --save-dev style-loader css-loader
```

### Setting up HtmlWebpackPlugin 

```bash
npm install --save-dev html-webpack-plugin
```

### Using webpack-dev-server
The webpack-dev-server provides you with a rudimentary web server and the ability to use live reloading.
```bash
npm install --save-dev webpack-dev-server

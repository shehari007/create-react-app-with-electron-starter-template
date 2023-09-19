# About Template

A complete starter template with all the configurations of electron (electron.js, preloader, CSP) with create-react-app application for developing desktop applications in a breeze.

# Advantages of this Basic Template

- Stock create-react-app template to work with electron integerated quick and easy start.
- Package json file updated with all the required scripts and build commands for electron no need to modify.
- electron.js & preloader.js are loaded with all the recommended secure steps e.g (CSP enabled in index.html, nodeIntegration is disabled, contentIsolation is enabled). You can work on it without worrying about XSS injection and other security issues.
- Stock webpack & ports configuration.

## Usage

Clone the repository

```bash
git clone https://github.com/shehari007/create-react-app-with-electron-starter-template.git
```
change the directory

```bash
cd create-react-app-with-electron-starter-template
```

Install dependencies

```bash
npm install
```

Run the project

```bash
npm run electron:start
```
`All done! project will start in window mode start developing for desktop platforms, Happy Hacking!`

## Build & Deploy Information

You can see the package.json file for build commands, for windows its:

```bash
npm run electron:package:win
```

This command will build and generate a NSIS .exe setup file with generated application, thats it install and share the app with others!

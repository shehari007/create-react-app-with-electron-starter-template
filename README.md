# About Template

A complete starter template with all the configurations of electron (electron.js, preloader, CSP) with create-react-app application for developing desktop applications in a breeze.
This template is based on detailed instruction on this blog <a href="https://mmazzarolo.com/blog/2021-08-12-building-an-electron-application-using-create-react-app/">View Blog Here</a>, This template only focuses on ready stock create-react-app to start with for creating apps and website in a single framework.

# Changelog (20/02/2024)

- Package Dependencies and DevDependencies are updated to latest versions.
- Electron ^29.0.0 (updated)
- Fixed @babel warning
- Node >=^20.10.0 (Tested & Working Fine)

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

In package.json file all commands are preloaded

## For Windows

```bash
npm run electron:package:win
```

This command will build and generate a NSIS .exe setup file with generated application, thats it install and share the app with others!

## For Linux

```bash
npm run electron:package:linux
```
This command will build and generate a .deb file with generated application, thats it install and share the app with others!

## For Mac

```bash
npm run electron:package:mac
```
This command will build and generate a .dmg file with generated application, thats it install and share the app with others!

## For Website

```bash
npm run build
```


## License

[MIT](https://choosealicense.com/licenses/mit/)


## Feedback

If you have any feedback, please reach out at shehariyar@gmail.com
dont't forget to give us a star if you like this project. ❤️

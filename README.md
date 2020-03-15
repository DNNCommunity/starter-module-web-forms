# starter-module-web-forms

**starter-module-web-forms** is a Web Forms module starter project for DNN Platform (formerly known as DotNetNuke).

## Installation

Clone this repo into a clean directory of your choice.

```bash
git clone https://github.com/DNNCommunity/starter-module-web-forms.git .
```

or...

Use [dnn-cli](https://www.npmjs.com/package/@dnncommunity/dnn-cli) to install into a directory of your choice.

Install **dnn-cli** using `yarn`:

```bash
yarn global add @dnncommunity/dnn-cli
```

Install **dnn-cli** using `npm`:

```bash
npm install -g @dnncommunity/dnn-cli
```

Create this starter project using `dnn-cli`:

```bash
dnn module web-forms
```

## Usage

1. Install DNN in a `.\Website` folder (root of directory in which this project is cloned)
2. Open solution file in Visual Studio 2019 (Run as Adminstrator...)
3. Build in `Debug` or `Release` mode

### Debug

By default this will compile the project and deploy it to the `.\Website` folder.  
- DLL and PDB files will be deployed to `.\Website\bin`
- All other relevant files will be deployed to `.\Website\DesktopModules\starter-module-web-forms`

### Release

By default this will create a module install package and place in `.\Website\Install\Module` so it will be in **Available Extensions** within DNN (SETTINGS > Extensions > Available Extensions).

## Contributing
Pull requests are welcome. Please open an issue first to document the bug or enhancement details.

## License
[![License: MIT](https://img.shields.io/badge/LICENSE-MIT-informational.svg)](https://opensource.org/licenses/MIT)
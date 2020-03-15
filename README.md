# starter-module-web-forms

[![License: MIT](https://img.shields.io/badge/LICENSE-MIT-informational.svg)](https://opensource.org/licenses/MIT)

**starter-module-web-forms** is a Web Forms module starter project for DNN Platform (formerly known as DotNetNuke).

## Installation

### Installation Option #1

Clone this repo into a clean directory of your choice.

```bash
git clone https://github.com/DNNCommunity/starter-module-web-forms.git .
```

### Installation Option #2

Use **dnn-cli**, which is [available as an npm package](https://www.npmjs.com/package/@dnncommunity/dnn-cli).  **dnn-cli** it can be installed via **yarn** or **npm**.

---
#### Install dnn-cli...

...via **yarn**:

```bash
yarn global add @dnncommunity/dnn-cli
```

...via **npm**:

```bash
npm install -g @dnncommunity/dnn-cli
```
---

Once you have **dnn-cli** installed install this starter project into a directory of your choice.

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
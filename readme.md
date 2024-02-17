# Generate Webpack -*Your Webpack Wizard!*

![Generate-Webpack Logo](https://cdn.jsdelivr.net/gh/aayushchouhan24/webpack-generator@master/logo-banner.png)

## Installation

```bash
npx gwp
```

## Usage

```bash
generate-webpack projectname -options
```

OR

```bash
gwp projectname -options
```

#### Options

| Options        | Short | Core Templates                                                                                                                                                                   | Description                         |
| ---------- | ----- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------- |
| `--core= ` | `-c`  | <p>webpack, three, three-basic, three-shader/three-shaders,<p/> three-master. For info click <a style =" color:#008CFF;  padding: 2px ; " href="#core-templates-list" >here.</a> | Select Core Template.               |
| `--nopkg`  | `-n`  | none                                                                                                                                                                      | Stop npm package auto installation. |

### Core Templates

| Core           | Description                                                                             |
| -------------- | --------------------------------------------------------------------------------------- |
| `three`        | Full three.js template via webpack with all needed things.                              |
| `three-basic`  | Basic three.js template with only essential things.                                     |
| `three-shader` | Basic three.js template with custom shaders {vertex and fragment}.                      |
| `three-master` | Master three.js template with custom shaders ,model,glass material,postprocessing ,etc. |

## Creator

Generate-Webpack was created by [Aayush Chouhan](https://github.com/aayushchouhan24).

## License

Generate-Webpack is open-source software licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Contact

For any questions or inquiries, you can reach us at <aayushchouhan24@gmail.com>.

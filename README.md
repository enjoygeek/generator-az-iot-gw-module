# Contributing

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

# Azure IoT Edge Module Generator
`generator-az-iot-gw-module` creates a base template to start a new edge module in Node.js.

## Prerequisites
1. Install latest [Node LTS](https://nodejs.org).
2. `npm install -g yo`.
3. `npm install -g generator-az-iot-gw-module`

## Usage
```
$yo az-iot-gw-module
```
*Note that this template will generate files in the current directory, so be sure always to run it against a new directory*

### Running module(s) on edge
Once the project is scaffolded, at the root folder run:
```
$npm install
$npm start
```

### Further Steps
1. Modify the source code of `printer.js` and `sensor.js` to provide more features.
2. Refer to [NODE Module Sample](https://github.com/Azure-Samples/azure-iot-gateway-samples/tree/master/js) to learn how to connect to [Azure IoT Hub](https://azure.microsoft.com/en-us/services/iot-hub/).

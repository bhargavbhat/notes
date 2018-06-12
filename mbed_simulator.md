### mbed Simulator Offline
Ref: https://os.mbed.com/blog/entry/introducing-mbed-simulator/

### Setup Steps
- Install [mbed-cli](mbed_cli.md)
- Install [NodeJS](https://nodejs.org/en/download/)
- Install [Emscripten SDK](https://kripken.github.io/emscripten-site/docs/getting_started/downloads.html#linux)

### Running
- [Source](https://github.com/kripken/emscripten/issues/5696) Emscripten Startup Script. Eg: `source ~/emsdk/emsdk_env.sh`
- Navigate to mbed project directory. Eg: `cd ~/mbed/mbed-os-example-blinky`
- Run Simulator. Eg: `mbed-simulator .`

### Getting mbed-cli up and running
Repo at: https://github.com/ARMmbed/mbed-cli

### Pre-reqs
```
sudo dpkg --add-architecture i386 && apt-get update && apt-get install libc6:i386 libncurses5:i386 libstdc++6:i386
```

### Installation
```
pip install mbed-cli
```

### Upgrade
```
pip install -U mbed-cli
```

### New Project
- `mbed new new_program`
- `cd new_program`
- `vi main.cpp`

### Import Project
- `mbed import https://mbed.org/teams/mbed/code/mbed_blinky/`
- `cd mbed-os-example-blinky`

### Config Settings
- `vi mbed_config.py` -> make sure to set the path to compiler i.e `GCC_ARM_PATH = "/usr/bin/arm-none-eabi-gcc"`

### Build
- `mbed compile --config -t ARM -m K66F`
- Check settings: `mbed compile --config -t ARM -m K66F`

### Export to other IDEs
- `mbed export -i uvision -m K66F`

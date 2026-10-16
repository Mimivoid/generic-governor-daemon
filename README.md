### About

- Adjusts the governor of each cpu between frequencies to either powersave or performance dynamically

#### Todo

- Use a json file for config of daemon
- Create systemd service file

#### Requirements
- cpupower
- hwloc
#### Compiling
``g++ test.cxx -Ofast -lhwloc -lcpupower -Wl,--gc-sections -Wl,--strip-debug -Wl,-Ofast``
#### Running
``sudo ./a.out``

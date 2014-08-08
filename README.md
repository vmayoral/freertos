#FreeRTOS skeleton for ROS 2 embedded

### Compile the code
```bash
make
```


### Debugging with gdb:
```bash
make gdb
```

Assuming that `.gdbinit` is configured in your `$HOME` as:
```
# GDB init file
target remote 127.0.0.1:3333
```

In another shell:
```bash
 arm-none-eabi-gdb main.elf
```
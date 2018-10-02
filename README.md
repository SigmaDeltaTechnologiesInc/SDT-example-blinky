# SDT-example-blinky

## Getting started with Blinky

Blinky example for Mbed OS

### Import the example code

From the command-line, import the example:

```
mbed import https://github.com/SigmaDeltaTechnologiesInc/SDT-example-blinky
cd SDT-example-blinky
```

### Compile

Invoke `mbed compile`, and specify the name of your platform and your favorite toolchain (`GCC_ARM`, `ARM`, `IAR`). 
For example, for the SDT64B and GCC_ARM:

```
mbed compile -m SDT64B -t GCC_ARM
```

### Program your board

1. Connect your mbed device to the computer over USB.
1. Copy the binary file to the mbed device.
1. Press the reset button to start the program.

The LED on your platform turns on and off.

## Troubleshooting

If you have problems, you can review the [documentation](https://os.mbed.com/docs/latest/tutorials/debugging.html) for suggestions on what could be wrong and how to fix it.

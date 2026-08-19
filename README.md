# Lab5-04: Downlink Accelerometer Data

Firmware that downlinks HK telemetry and accelerometer samples on command.

## Web Serial Monitor

Open in **Chrome or Edge**, then **Add Port** → **Connect** (38400 baud):

**https://hepta-sat-training.github.io/HEPTA-SAT-Serial_Monitor/**

- HK lines appear every second in the output pane.
- Type `a` in the input bar and press **Enter** to receive 10 accelerometer lines (`AX=...,AY=...,AZ=...`).

## Firmware

Open `Lab5-04_Downlink_Accelerometer_Data.ino` in the Arduino IDE and upload to your board. For library and submodule setup, see [src/README.md](src/README.md).

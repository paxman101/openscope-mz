This is a fork for the OpenScope MZ firmware that implements a workaround for getting the board to run with a missing IC13 or wifi module. 
Inspired by a board I received in such a condition. 
The workaround is a very hacky solution wherein some checks that stalled execution before are removed. 
Effect on non-wifi based functionality unknown.
# OpenScope MZ

Firmware for the OpenScope MZ - an open source, multi-function, electronic instrumentation device that can be controlled using a computer or mobile device.

### Resources
 * [Buy and OpenScope MZ](http://store.digilentinc.com/openscope-mz-open-source-all-in-one-instrumentation/)
 * [Getting Started Guide for non-developer](https://reference.digilentinc.com/learn/instrumentation/tutorials/openscope-mz/getting-started)
 * [Reference Material](https://reference.digilentinc.com/reference/instrumentation/openscope-mz/start)
 * [Digilent Instrumentation Protocol](https://reference.digilentinc.com/reference/software/digilent-instrumentation-protocol/start)
 * [WaveForms Live](https://reference.digilentinc.com/reference/software/waveforms-live/start)

### Precompiled Binaries
Precompiled binaries available [here](https://reference.digilentinc.com/reference/instrumentation/openscope-mz/previous-versions).

### Building from source
1. Install Arduino **1.6.9** IDE.  
  * (Other versions of the Arduino IDE have not been tested and may not work).
2. Install the Digilent Core for Arduino as described [here](https://reference.digilentinc.com/learn/software/tutorials/digilent-core-install/start).
3. Clone this repository into a folder named 'OpenScope' (the foldername must match for the .ino to open correctly).
  * <code>git clone https://github.com/Digilent/openscope-mz.git OpenScope</code>
4. Copy the supporting libraries from OpenScope/libraries into the Arduion libraries folder (See **File>>Preferences>>Sketchook locaion** in Arduino IDE).
4. Open OpenScope.ino in the Arduino IDE.
5. Connect the OpenScope MZ to the computer via USB.
5. Click **Tools>>Board>>OpenScope**.
6. Click **Tools>>Port** and select the COM port associated with the OpenScope MZ.
6. Click **Upload** to compile the firmware and upload it to the OpenScope MZ.

### Feedback and Support
[Digilent Forums - WaveForms Live and OpenScope MZ](https://forum.digilentinc.com/forum/30-waveforms-live-and-openscope-mz/)

### Credits
Author: Keith Vogel
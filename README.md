[![PCA9536](PCA9536_I2CIO.png)](https://store.ncd.io/product/pca9536-digital-4-channel-input-output-i2c-mini-module/).

# PCA9536

The PCA9536 is a general purpose programmable 4-Channel digital input/output controller. In this design, we make all 4 pins available for user applications via a small terminal block. The address of the PCA9536 is fixed at 0x64, so only one of these devices may be attached to a single I2C port.
This Device is available from www.ncd.io

[SKU: PCA9536]

(https://store.ncd.io/product/pca9536-digital-4-channel-input-output-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface PCA9536 input output module With Raspberry Pi:

1. <a href="https://store.ncd.io/product/pca9536-digital-4-channel-input-output-i2c-mini-module/">PCA9536 Input Output Module</a>

2. <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>

3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python PCA9536.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.

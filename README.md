# Raspberry Pi Home Automation - Node-RED

Node-RED project for Raspberry Pi home automation.

Features:
- GPIO outputs control
- I2C inputs monitoring
- REST API
- Device abstraction layer
- Test environment

## Tabs

### inputs
Reads MCP23017 inputs over I2C.

### outputs
Exposes REST endpoints:
/outputs/1
/outputs/2
...

### devices
Device-oriented API.

### test
Testing environment.

## Requirements

- Raspberry Pi
- Node-RED
- node-red-node-pi-gpio
- node-red-node-pi-i2c
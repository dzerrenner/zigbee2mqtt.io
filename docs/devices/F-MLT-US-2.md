---
title: "SmartThings F-MLT-US-2 control via MQTT"
description: "Integrate your SmartThings F-MLT-US-2 via Zigbee2MQTT with whatever smart home infrastructure you are using without the vendor's bridge or gateway."
addedAt: 2019-07-22T20:08:17Z
pageClass: device-page
---

<!-- !!!! -->
<!-- ATTENTION: This file is auto-generated through docgen! -->
<!-- You can only edit the "Notes"-Section between the two comment lines "Notes BEGIN" and "Notes END". -->
<!-- Do not use h1 or h2 heading within "## Notes"-Section. -->
<!-- !!!! -->

# SmartThings F-MLT-US-2

|     |     |
|-----|-----|
| Model | F-MLT-US-2  |
| Vendor  | SmartThings  |
| Description | Multipurpose sensor (2016 model) |
| Exposes | temperature, contact, battery_low, tamper, battery, moving, x_axis, y_axis, z_axis, linkquality |
| Picture | ![SmartThings F-MLT-US-2](https://www.zigbee2mqtt.io/images/devices/F-MLT-US-2.jpg) |


<!-- Notes BEGIN: You can edit here. Add "## Notes" headline if not already present. -->

## Notes

### Pairing
When pairing, make sure to keep the sensor awake for 20 seconds by opening and closing the contact every second.

<!-- Notes END: Do not edit below this line -->


## Options
*[How to use device type specific configuration](../guide/configuration/devices-groups.md#specific-device-options)*

* `temperature_precision`: Number of digits after decimal point for temperature, takes into effect on next report of device. The value must be a number with a minimum value of `0` and with a with a maximum value of `3`

* `temperature_calibration`: Calibrates the temperature value (absolute offset), takes into effect on next report of device. The value must be a number.


## Exposes

### Temperature (numeric)
Measured temperature value.
Value can be found in the published state on the `temperature` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `°C`.

### Contact (binary)
Indicates if the contact is closed (= true) or open (= false).
Value can be found in the published state on the `contact` property.
It's not possible to read (`/get`) or write (`/set`) this value.
If value equals `false` contact is ON, if `true` OFF.

### Battery_low (binary)
Indicates if the battery of this device is almost empty.
Value can be found in the published state on the `battery_low` property.
It's not possible to read (`/get`) or write (`/set`) this value.
If value equals `true` battery_low is ON, if `false` OFF.

### Tamper (binary)
Indicates whether the device is tampered.
Value can be found in the published state on the `tamper` property.
It's not possible to read (`/get`) or write (`/set`) this value.
If value equals `true` tamper is ON, if `false` OFF.

### Battery (numeric)
Remaining battery in %.
Value can be found in the published state on the `battery` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The minimal value is `0` and the maximum value is `100`.
The unit of this value is `%`.

### Moving (binary)
Indicates if the device is moving.
Value can be found in the published state on the `moving` property.
It's not possible to read (`/get`) or write (`/set`) this value.
If value equals `true` moving is ON, if `false` OFF.

### X_axis (numeric)
Accelerometer X value.
Value can be found in the published state on the `x_axis` property.
It's not possible to read (`/get`) or write (`/set`) this value.

### Y_axis (numeric)
Accelerometer Y value.
Value can be found in the published state on the `y_axis` property.
It's not possible to read (`/get`) or write (`/set`) this value.

### Z_axis (numeric)
Accelerometer Z value.
Value can be found in the published state on the `z_axis` property.
It's not possible to read (`/get`) or write (`/set`) this value.

### Linkquality (numeric)
Link quality (signal strength).
Value can be found in the published state on the `linkquality` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The minimal value is `0` and the maximum value is `255`.
The unit of this value is `lqi`.


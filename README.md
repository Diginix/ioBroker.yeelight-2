![Logo](admin/yeelight.png)
# ioBroker.yeelight2
=================

[![NPM version](http://img.shields.io/npm/v/iobroker.yeelight2.svg)](https://www.npmjs.com/package/iobroker.yeelight2)
[![Downloads](https://img.shields.io/npm/dm/iobroker.yeelight2.svg)](https://www.npmjs.com/package/iobroker.yeelight2)

[![NPM](https://nodei.co/npm/iobroker.yeelight2.png?downloads=true)](https://nodei.co/npm/iobroker.yeelight2/)

**Tests:** Linux/Mac: [![Travis-CI](https://api.travis-ci.org/MeisterTR/ioBroker.yeelight2.svg?branch=master)](https://travis-ci.org/MeisterTR/ioBroker.yeelight2)
Windows: [![AppVeyor](https://ci.appveyor.com/api/projects/status/github/MeisterTR/ioBroker.yeelight2?branch=master&svg=true)](https://ci.appveyor.com/project/MeisterTR/ioBroker-yeelight2/)


[Deutsche Beschreibung hier](README_de.md)

This adapter control your Yeelight device

## Installation
for RGB Bulbs you have to enable the LAN in the settings of the yeelight app.

## Config
you can add manually devices or find devices in network. the basic port is 55443. if you want, you can change the name, ip, port and smartname

### smartname
if you type in a smartname, the device is add to the iobroker.cloud and can control by alexa. 

### Find device
with this button you can scan your Network for devices, if something is found, the divices added to the table. It takes about 20 seconds to scan the network. if the devices not found, the Lan mode is not enabled or the bulbs are in a nother network.


## Changelog
### 0.2.8 (2018-06-01)
* (MeisterTR) fixed bug wit port, fixed set ct by alexa
### 0.2.6 (2018-05-31)
* (MeisterTR) fixed manny bugs.
### 0.2.0 (2018-03-07)
* (MeisterTR) many changes add smartname Option, add manual devices, many fixes
* (MeisterTR) fix role for alexa
### 0.1.1 (2018-03-07)
* (MeisterTR)return to default value when turn on
* (MeisterTR)fix role for alexa
### 0.1.0 (2018-03-07)
* (MeisterTR) many changes, add hue and sat for alexa control
### 0.0.2 (2018-03-07)
* (MeisterTR) objects not overwirte after restart
### 0.0.2 (2018-03-07)
* (MeisterTR) testing added, log changed
### 0.0.1 (2018-01-29)
* (cahek2202) initinal version



base from: adb backup https://github.com/cahek2202/ioBroker.yeelight

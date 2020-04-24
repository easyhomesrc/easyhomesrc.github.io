---
layout: post
permalink: /zigbee/device_types/
title:  "ZigBee - Device Types"
post_title: "ZigBee Device Types"
date:   2020-04-24 11:48:00 +0800
categories: 
---

# ZigBee Device Types

用 `ProfileId` 与 `DeviceId` 区分 ZigBee 设备，不在下面列表中的设备，视为 `unknown` 设备。

## ZHA Devices 

ProfileId `0x0104`

### Lighting (灯)

#### On/Off Lighting

- 0x0100
- 0x010A

#### DIM Lighting

- 0x0101

#### Color Temperature Lighting (CCT)

- 0x010C 

#### Color Lighting (RGBW)

- Undefined

#### Color Lighting (RGBCCT)

- 0x010D 
- 0x0102

### Rmeote Control (遥控)

#### On/Off Remote Control 

- 0x0000

#### DIM Remote Control 

- 0x0001
- 0x0103
- 0x0104

#### Color Remote Control 

- 0x0105

### Outlet (插座)

- 0x0051 

### Curtain (窗帘)

- 0x0203 

## ZLL Devices 

ProfileId `0xC05E`

### Lighting (灯)

#### On/Off Lighting

- 0x0000

#### DIM Lighting

- 0x0100

#### Color Temperature Lighting (CCT)

- 0x0220

#### Color Lighting (RGBW)

- Undefined

#### Color Ligthing (RGBCCT)

- 0x0200
- 0x0210

### Remote Control (遥控器)

#### Color Remote Control 

- 0x0800

#### Color Scene Remote Control 

- 0x0810 

#### DIM Remote Control 

- 0x0820

#### Scene Remote Control 

- 0x0830
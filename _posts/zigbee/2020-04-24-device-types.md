---
layout: post
permalink: /zigbee/device-types/
title:  "ZigBee - Device Types"
post_title: "ZigBee Device Types"
date:   2020-04-24 13:58:00 +0800
categories: 
---

用 `ProfileId` 与 `DeviceId` 区分 ZigBee 设备，不在下面列表中的设备，视为 `unknown` 设备。

## Profile Id

<table>
	<tr>
		<th>Profile Id</th>
		<th>Type</th>
	</tr>
	<tr>
		<td>0x0104</td>
		<td>ZHA</td>
	</tr>
	<tr>
		<td>0xC05E</td>
		<td>ZLL</td>
	</tr>
</table>


## ZHA Devices 

ProfileId `0x0104`

<table>
	<tr>
		<th>Device Type</th>
		<th>Sub Device Type</th>
		<th>Device Id</th>
	</tr>
	<tr>
		<td rowspan="7">Lighting</td>
		<td rowspan="2">On/Off</td>
		<td>0x0100</td>
	</tr>
	<tr>
		<td>0x010A</td>
	</tr>
	<tr>
		<td>DIM</td>
		<td>0x0101</td>
	</tr>
	<tr>
		<td>Color Temperature (CCT)</td>
		<td>0x010C</td>
	</tr>
	<tr>
		<td>Color (RGBW)</td>
		<td>-</td>
	</tr>
	<tr>
		<td rowspan="2">Color (RGBCCT)</td>
		<td>0x010D</td>
	</tr>
	<tr>
		<td>0x0102</td>
	</tr>
	<tr>
		<td rowspan="5">Remote Control</td>
		<td>On/Off</td>
		<td>0x0000</td>
	</tr>
	<tr>
		<td rowspan="3">DIM</td>
		<td>0x0001</td>
	</tr>
	<tr>
		<td>0x0103</td>
	</tr>
	<tr>
		<td>0x0104</td>
	</tr>
	<tr>
		<td>Color</td>
		<td>0x0105</td>
	</tr>
	<tr>
		<td>Outlet</td>
		<td>-</td>
		<td>0x0051</td>
	</tr>
	<tr>
		<td>Curtain</td>
		<td>-</td>
		<td>0x0203</td>
	</tr>
</table>

## ZLL Devices 

ProfileId `0xC05E`

<table>
	<tr>
		<th>Device Type</th>
		<th>Sub Device Type</th>
		<th>Device Id</th>
	</tr>
	<tr>
		<td rowspan="6">Lighting</td>
		<td>On/Off</td>
		<td>0x0000</td>
	</tr>
	<tr>
		<td>DIM</td>
		<td>0x0100</td>
	</tr>
	<tr>
		<td>Color Temperature (CCT)</td>
		<td>0x0220</td>
	</tr>
	<tr>
		<td>Color (RGBW)</td>
		<td>-</td>
	</tr>
	<tr>
		<td rowspan="2">Color (RGBCCT)</td>
		<td>0x0200</td>
	</tr>
	<tr>
		<td>0x0210</td>
	</tr>
	<tr>
		<td rowspan="4">Remote Control</td>
		<td>Color</td>
		<td>0x0800</td>
	</tr>
	<tr>
		<td>Color Scene</td>
		<td>0x0810</td>
	</tr>
	<tr>
		<td>DIM</td>
		<td>0x0820</td>
	</tr>
	<tr>
		<td>Scene</td>
		<td>0x0830</td>
	</tr>	
</table>

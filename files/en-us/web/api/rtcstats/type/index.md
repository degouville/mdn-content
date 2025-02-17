---
title: RTCStats.type
slug: Web/API/RTCStats/type
page-type: web-api-instance-property
tags:
  - API
  - Property
  - RTCStats
  - Report
  - Statistics
  - Stats
  - Type
  - WebRTC
  - WebRTC API
  - rtc
browser-compat: api.RTCStats.type
---
{{APIRef("WebRTC")}}

The {{domxref("RTCStats")}} dictionary's property
**`type`** is a string which specifies the type of statistic
represented by the object, where the permitted values are drawn from the enum type
{{domxref("RTCStatsType")}}.

The string can be used to determine which of the
{{domxref("RTCStats")}}-based dictionaries are the foundation of the statistics object.

## Value

A string which specifies which type of statistic is represented by
the object. The string comes from the {{domxref("RTCStatsType")}} enum and corresponds to
one of the {{domxref("RTCStats")}}-based statistic object types.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

---
date: 2018-01-01
title: Browser Requirements
description: Guide on browser requirements for Exokit Web.
redirect_from:
  - /documentation/browser-requirements/
categories:
  - getting-started
type: Document
set: getting-started
set_order: 2
---

This page covers any browsers requirements needed before running Exokit Web.

# WebXR Compatiblity
The [WebXR Device API](https://github.com/immersive-web/webxr/blob/master/explainer.md) provides access to input and output capabilities commonly associated with Virtual Reality (VR) and Augmented Reality (AR) devices. It allows you develop and host VR and AR experiences on the web. Browsers must have WebVR or WebXR compatibility to enter XR mode on Exokit Web.

# Chrome
To run Exokit Web with Chrome, you must run Chrome 66 and later.

If you are entering XR mode, disable the `chrome://flags/#xr-sandbox` flag. (The URL must be entered manually.)

If you are using an **OpenVR** headset, enable the `chrome://flags/#openvr` flag.

If you are using an **Oculus** headset, enable the `chrome://flags/#oculus-vr` flag.

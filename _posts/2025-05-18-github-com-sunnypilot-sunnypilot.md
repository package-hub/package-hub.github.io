---
title: sunnypilot
categories: ['python', 'autopilot', 'comma']
---
## [sunnypilot](https://github.com/sunnypilot/sunnypilot)

### sunnypilot is an open source driver assistance system. sunnypilot offers the user a unique driving experience for over 300 supported car makes and models with modified behaviors of driving assist engagements. sunnypilot complies with the safety policy from comma.ai's openpilot as accurately as possible.

- [**Modified Assistive Driving Safety (MADS)**](#modified-assistive-driving-safety-mads) - Automatic Lane Centering (ALC) / Lane Keep Assist System (LKAS) and Adaptive Cruise Control (ACC) / Smart Cruise Control (SCC) can be engaged independently of each other
- [**Dynamic Lane Profile (DLP)**](#dynamic-lane-profile-dlp) - Dynamically switch lane profile (between Laneful and Laneless) based on lane recognition confidence
- [**Enhanced Speed Control**](#enhanced-speed-control) - Automatically adjust cruise control speed using vision model, OpenStreetMap (OSM) data, and/or Speed Limit control (SLC) without user interaction
    * Vision-based Turn Speed Control (V-TSC) - lower speed when going around corners using vision model
    * Map-Data-based Turn Speed Control (M-TSC) - lower speed when going around corners using OSM data[^1]
    * Speed Limit Control (SLC) - Set speed limit based on map data or car interface (if applicable)
    * HKG only: Highway Driving Assist (HDA) status integration - Use cars native speed sign detection to set desired speed (on applicable HKG cars only)
- [**Gap Adjust Cruise (GAC)**](#gap-adjust-cruise) - Allow `GAP`/`INTERVAL`/`DISTANCE` button on the steering wheel or on-screen button to adjust the follow distance from the lead car. See table below for options
- [**Quiet Drive 🤫**](#-quiet-drive) - Toggle to mute all notification sounds (excluding driver safety warnings)
- [**Auto Lane Change Timer**](#Auto-Lane-Change-Timer) - Set a timer to delay the auto lane change operation when the blinker is used. No nudge on the steering wheel is required to auto lane change if a timer is set
- [**Force Car Recognition (FCR)**](#Force-Car-Recognition-) - Use a selector to force your car to be recognized by sunnypilot
- [**Fix sunnypilot No Offroad**](#Fix-sunnypilot-No-Offroad) - Enforce sunnypilot to go offroad and turns off after shutting down the car. This feature fixes non-official devices running sunnypilot without comma power
- [**Enable ACC+MADS with RES+/SET-**](#Enable-ACC+MADS-with-RES+/SET-) - Engage both ACC and MADS with a single press of RES+ or SET- button
- [**Offline OSM Maps**](#Offline-OSM-Maps) - OSM database can now be downloaded locally for offline use[^2]. This enables offline SLC, V-TSC and M-TSC. Currently available for US South, US West, US Northeast, Florida, Taiwan, South Africa and New Zealand
- [**Various Live Tuning**](#Various-Live-Tuning) - Ability to tailor your driving experience on the fly:
    * Enforce Torque Lateral Control - Use the newest [torque controller](https://blog.comma.ai/0815release/#torque-controller) for all vehicles.
    * Torque Lateral Control Live Tune - Ability to adjust the torque controller’s `FRICTION` and `LAT_ACCEL_FACTOR` values to suit your vehicle.
    * Torque Lateral Controller Self-Tune - Enable automatic turning for the Torque controller.

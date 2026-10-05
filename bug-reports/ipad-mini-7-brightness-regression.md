# iPad mini 7 – Ambient Brightness System Threshold Regression

## Test Environment

- **Platform:** Core iPadOS System
- **Device:** iPad mini (7th Generation)
- **Build Found:** iPadOS 18.7.1
- **Build Verified:** iPadOS 18.7.2 RC
- **Severity:** Major / OS Regression

## Defect Summary

A critical operating system logic regression improperly triggered the hardware High Brightness thermal threshold at an ambient output of just 10% brightness. Device Monitor telemetry was implemented to baseline and isolate the system regression against historical parameters.

## Steps to Reproduce

1. Deploy target hardware in a stable room temperature environment.
2. Manually increment the display brightness slider from 0% past 10%.
3. Observe incorrect system flag warning indicating thermal peak limits.

## Resolution Status

Mitigated and deployed by Apple Core OS team in the official iPadOS 18.7.2 public rollout.

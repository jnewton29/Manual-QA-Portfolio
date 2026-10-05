# Aloha Browser – Appearance Tab Null-Pointer Crash

## Test Environment

- **Platform:** iPadOS
- **Application:** Aloha Browser
- **Device:** iPad (10th Generation)
- **App Version Found:** 7.8.0
- **OS Version:** iPadOS 26.0 Beta
- **Fix Verified:** Aloha Browser 7.11.0
- **Severity:** Major / Blocker
- **Status:** Fixed and Verified

## Defect Summary

Aloha Browser experienced an immediate application crash when the Appearance section was opened from Settings on iPadOS 26.0 Beta.

The issue resulted in repeated application termination and prevented access to appearance customization settings.

Crash logs and supporting information were provided to the developer.

## Steps to Reproduce

1. Launch Aloha Browser.
2. Navigate to **Settings**.
3. Select **Appearance**.
4. Observe the application crash.

## Expected Result

The Appearance settings should open normally and allow the user to access available appearance and theme options.

## Actual Result

The application immediately crashes after the Appearance section is selected.

## Evidence

Crash logs and a screen recording were collected and submitted to the developer.

## Resolution / Verification

The issue was resolved in Aloha Browser version 7.11.0.

Regression testing after the update confirmed that the Appearance section could be accessed without reproducing the crash.

# Device Monitor – Restore Purchase Text Overlay Glitch

## Test Environment

- **Platform:** iPadOS
- **Application:** Device Monitor
- **Device:** iPad (10th Generation)
- **App Version Found:** 26.0
- **Fix Verified:** 26.1.0
- **Severity:** Minor / UI Layout
- **Status:** Fixed and Verified

## Defect Summary

A UI layout issue within the application's purchase section caused text to overlap the Restore Purchases button.

The overlapping content interfered with interaction with the Restore Purchases button and affected the layout on iPad.

## Steps to Reproduce

1. Launch Device Monitor.
2. Navigate to the in-app purchase section.
3. Scroll to the bottom of the purchase screen.
4. Observe the text overlapping the Restore Purchases button.

## Expected Result

Text and interactive elements should render within their designated areas without overlapping the Restore Purchases button.

The Restore Purchases button should remain clearly visible and accessible.

## Actual Result

Text rendered over the Restore Purchases button, creating a layout collision and interfering with normal interaction.

## Resolution / Verification

The issue was resolved in Device Monitor version 26.1.0.

The publisher included the correction as part of graphical improvements and responsive layout scaling changes.

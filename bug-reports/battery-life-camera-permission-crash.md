# Battery Life App – Missing Camera Permission Null Pointer Exception

## Test Environment

- **Platform:** Cross-Platform iOS / iPadOS
- **Devices Tested:**
  - iPod touch (7th Generation)
  - iPad (7th Generation)
  - iPad Pro (M2)
  - iPhone 15 Pro
  - iPad mini (7th Generation)
  - iPad (10th Generation)
- **Build Found:** v25.10.2
- **Build Verified:** v26.8.3
- **Severity:** Major / Functional Crash

## Defect Summary

Attempting to append or capture an asset inside the built-in feedback workspace triggered an unhandled null pointer crash across all tested hardware variations.

Decoded console crash outputs indicated a missing application call framework to safely handle or request device camera privacy permissions.

## Steps to Reproduce

1. Access the internal Customer Feedback panel.
2. Select the attachment clip icon to choose a media source.
3. Observe application termination without a permission modal fallback.

## Evidence

Crash behavior was reproduced across multiple iOS and iPadOS devices.

The issue was reported through Apple's App Store compliance process citing App Store Review Guideline 2.1 and Privacy Guideline 5.1.1.

## Resolution Status

Resolved in v26.8.3 following the App Store compliance report.

As a workaround, the developer removed the **Take Photo** feature from the in-app feedback portal, eliminating the camera permission path that triggered the crash.

Fix verified after updating to v26.8.3.

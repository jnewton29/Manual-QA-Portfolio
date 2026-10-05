# iPad 10th Gen – Brightness Regression Return

## Test Environment

- **Platform:** Core iPadOS System
- **Device:** iPad (10th Generation)
- **Build Found:** iPadOS 26.1 Public
- **Build Verified:** iPadOS 26.2 Beta 1
- **Severity:** Major / Regression Re-emergence

## Defect Summary

The identical 10% peak display threshold regression previously isolated in iPadOS 18.7.1 unexpectedly re-emerged within the final public release of iPadOS 26.1, despite having passed verification checks as stable during the 26.1 RC cycle. Log parameters matched the original telemetry signatures.

## Steps to Reproduce

1. Update iPad (10th Generation) to the public release of iPadOS 26.1.
2. Advance the display luminance curve.
3. Confirm recurrence of early high-brightness alert flags.

## Resolution Status

Fixed and verified in subsequent branch testing via iPadOS 26.2 Beta 1.

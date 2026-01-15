# Lab setup (Windows + Sysmon)

## Goal
Generate high-quality Windows security telemetry so I can build and test detections (Sigma + KQL).

## What you need
- A Windows 10/11 VM (local)
- Sysmon installed
- Sysmon config applied (SwiftOnSecurity)

## Steps
1. Create a Windows VM and update it fully.
2. Install Sysmon.
3. Apply a Sysmon configuration.
4. Verify Sysmon is logging.

## Verify logging
Open Event Viewer:
- Applications and Services Logs
  - Microsoft
    - Windows
      - Sysmon
        - Operational

You should see events (e.g., process creation, network connections).

## Notes
This repo is for defensive testing in a lab environment only.

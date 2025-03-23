# SAFECAM

Product: https://safecam.my/pages/x300

Version: X300

## Finding 1: Same Default Credentials with Hardcoded FTP Credentials in APK 

The SAFECAM X300 dashcam ships with identical default credentials for all devices. This allows attackers to use the same credentials to connect to any SAFECAM X3 dashcams with default settings, within range, enabling unauthorized access to multiple devices. An attacker can then connect to the dashcam's FTP server using hardcoded FTP credentials found in the mobile app (Viidure v1.5) and remotely download all recorded video footage, exposing sensitive data.

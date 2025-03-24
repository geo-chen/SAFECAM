# SAFECAM

**Product**: https://safecam.my/pages/x300

**Version**: X300

## Finding 1: Same Default Credentials with Hardcoded FTP Credentials in APK 

**Description**: The SAFECAM X300 dashcam ships with identical default credentials for all devices. This allows attackers to use the same credentials to connect to any SAFECAM X3 dashcams with default settings, within range, enabling unauthorized access to multiple devices. An attacker can then connect to the dashcam's FTP server using hardcoded FTP credentials found in the mobile app (Viidure v2.1.1.250317) and remotely download all recorded video footage, exposing sensitive data.

<img width="339" alt="image" src="https://github.com/user-attachments/assets/af74e4a3-0014-4f4f-a58b-6e263e637d94" />


**Vulnerability Type**: Insecure Permissions

**Vendor of Product**: SAFECAM

**Affected Product Code Base**: Viidure v2.1.1.250317

**Affected Component**: FTP Server

**Attack Type**: Remote

**Impact Code execution**: False

**Impact Information Disclosure**: True

**Attack Vectors**: An attacker connected to the dashcam's network can access dashcam's FTP server using plaintext credentials from APK and dump all sensitive video recordings.

**Has vendor confirmed or acknowledged the vulnerability?**: No

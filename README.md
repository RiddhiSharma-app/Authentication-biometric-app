<h1>Biometric Authentication</h1>

<h2>Description</h2>
This provides means to perform local, on-device authentication of the user.
On supported devices, this includes authentication with biometrics such as fingerprint or facial recognition.

Currently the following biometric types are implemented:

- BiometricType.face
- BiometricType.fingerprint
- BiometricType.weak
- BiometricType.strong

Dialogs
The plugin provides default dialogs for the following cases:

Passcode/PIN/Pattern Not Set: The user has not yet configured a passcode on iOS or PIN/pattern on Android.
Biometrics Not Enrolled: The user has not enrolled any biometrics on the device.
If a user does not have the necessary authentication enrolled when authenticate is called, they will be given the option to enroll at that point, or cancel authentication.


<br />



<h2>Images :</h2>

<p align="center">
Login: <br/>
<img src="https://i.imgur.com/SlJHBrf.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<br />
<br />
Login: <br/>
<img src="https://i.imgur.com/MwARP4C.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>


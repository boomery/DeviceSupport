# DeviceSupport
A quick fix for the "Xcode Could not locate device support files" error.

![869f4d69133342a334d736b902f27147](https://github.com/user-attachments/assets/12337c06-aecd-4702-a0c1-d16b4a9f450e)

## Steps
1：press shift+command+g buttton，input  "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport" to open folder。

2：Download the .zip file that matches your device's iOS version.

3：Extract the .zip file, then copy the extracted folder into your DeviceSupport directory.

4：Reconnect your iOS device to your Mac and try running your project again.

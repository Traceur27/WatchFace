# WatchFace for Android Wear
My simple project for digital face for Sony Smartwatch 3

## Setup

### Before starting
* Edit build configuration -> Launch : Nothing

### Make your watch being recognizable by Ubuntu
1. Enable debugging in programmers options on Watch
2. Create 51-android.rules and paste there some rules: https://github.com/M0Rf30/android-udev-rules/blob/master/51-android.rules
```bash
cd /etc/udev/rules.d
sudo touch 51-android.rules
sudo gedit 51-android.rules
```
3. Give the file necessary rights
```bash
sudo chmod a+r 51-android.rules
```
4. Reconnect your watch

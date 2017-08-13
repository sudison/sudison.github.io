In case you got "adbd cannot run as root in production builds" error, when executing "adb root".
here are the instructions to work arond the issue without flashing a developer build, which will wipe out all your data:
0. bootloader is unlocked.
1. Android is rooted.
2. Install adbd insecure: https://forum.xda-developers.com/showthread.php?t=1687590
3. For android 6+, needs to disable selinux:
	adb shell
	su
	setenforce 0
	

L SPeed Vector
==============

L Speed is a mod that combines some scripts and little tweaks in one package which is aimed to improve performance, reduce lags and expand battery life.
Originally developed for the LG L Series, now this mod is expanded and modified accordingly to run on any device!
This mod will work on any device.
All you need to ensure is that your phone is running Android!
It will work from Android 2.3 (Gingerbread) to Android 6.0.1 (Marshmallow)

-----------------------------------------

## Installation

1. Uninstall previous versions of LSpeed [ if your version is 3.3 or below ]. 

**Note**: If your version is 4.0 and above you can skip this step.

2. Install the busybox from [HERE](https://play.google.com/store/apps/details?id=stericson.busybox&hl=en%22) (Stericson) 

**Note**: It is strongly advised to use this busybox to have full compatibility with the Mod.

3. Download [LSpeed file](https://www.androidfilehost.com/?w=files&flid=41769)

4. Use a file manager with ROOT access and delete old LS file from /system/bin/ 

**Note**: Only "LS", not "ls" neither "lsmod", they are part of Busybox

5. Rename the downloaded file to LS (without any extension)

6. Copy the renamed file to /system/bin 

7. Set permission to 755 

```
su
mount -o remount,rw /system
chmod 755 /system/bin/LS
```

or
 
Simply use a file-manager to set 755 permissions

8. After these steps you can wipe cache and dalvik from recovery (recommended) 

9. Run the script as usual from terminal

```
su
LS
```

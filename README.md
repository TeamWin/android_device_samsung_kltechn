## TWRP device tree for Galaxy S5 (China & China Duos)

Add to `.repo/local_manifests/kltechn.xml`:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
	<project path="device/samsung/kltechn" name="android_device_samsung_kltechn" remote="TeamWin" revision="android-6.0" />
</manifest>
```

Then run `repo sync` to check it out.

Kernel sources are available at: https://github.com/jcadduono/nethunter_kernel_klte/tree/twrp-6.0


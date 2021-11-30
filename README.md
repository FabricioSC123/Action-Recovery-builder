# Use Github Action to compile Recovery
```
Support OFRP, SHRP, TWRP compilation and production
```
---

## Release Notes
```
= 2021/11/29
- Update LIBRARY_NAME rules, now LIBRARY_NAME is not required
  (If you need to continue to use it, you need to add'_', such as'omni_')
```
```
= 2021/11/20
- Added default upload boot.img
```
```
= 2021/11/17
- Add compilation mode support (in vendorsetup: userdebug/eng/debug)
```
```
= 2021/10/31
- Add Common device support [@Xpsoted](https://github.com/Xpsoted)
```

```
= 2021/10/30
- Optimize the file uploading method, support the output of OFRP, SHRP card upgrade package and original image
- Simplify part of the manufacturing process
```

```
= 2021/10/29: 
- Refactored version 2.0
- Completely reconstruct the use logic to reduce the difficulty of use
- Optimize the parameter transfer part, now you can run multiple Workers at the same time
- TWRP compilation test passed
- OFRP compile test passed
- SHRP compile test passed
```

-----

## Parameter Description

| Name | Description | Example |
| ------------ | -------------------- | ------------ |
| `LIBRARY_NAME` | Source type | omni |
| `LIBRARY_URL` | Source address | https://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git |
| `LIBRARY_BRANCH` | Source branch | twrp-9.0 |
| `DEVICE_URL` | Device address | https://github.com/azwhikaru/twrp_device_xiaomi_archytas |
| `DEVICE_BRANCH` | Device branch | twrp-9.0 |
| `DEVICE_PATH` | Device location | device/xiaomi/Archytas |
| `DEVICE_NAME` | Model name | Archytas |
| `DEVICE_TYPE` | Compilation mode | eng/userdebug/debug |

-----

## how to use
```
For example, your username is: Fun-114514
```
#### 1、Click on the upper right corner of this warehouse 'Fork'
![](https://i.bmp.ovh/imgs/2021/10/6b6ed9f29e732372.png)
#### 2、After waiting for the automatic redirection, you will see your own username
![](https://i.bmp.ovh/imgs/2021/10/66cfe324c0ebb69b.png)
#### 3、Click on 'Actions - Make Recovery'
![](https://i.bmp.ovh/imgs/2021/10/23896d1b66292047.png)
#### 4、Click on 'Run workflow' and fill in according to the above'parameter description'
![](https://i.bmp.ovh/imgs/2021/10/9cb7871267cf2f53.png)
#### 5、After filling in, click 'Run workflow' to start running

-----

## Compilation result
Can be downloaded at [Release](../../releases)

-----
## Remark

#### TeamWin Recovery Project: https://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git
#### OrangeFox Recovery Project: https://gitlab.com/OrangeFox/Manifest.git
#### SKYHAWK Recovery Project: https://github.com/SHRP/platform_manifest_twrp_omni.git

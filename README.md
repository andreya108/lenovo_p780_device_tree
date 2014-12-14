1) copyto /something/omni/device/lenovo/P780

2) put prebuilt kernel to prebuilt dir

3) to build use commands:

```. build/envsetup.sh

lunch full_P780-userdebug

make -j4 recoveryimage V=s
```
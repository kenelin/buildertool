# Builder Tools #

These tools are used to build Android APKs which only contain resources.

## Repacked Android SDK ##

Currently use these Android SDK components:

 1. tools r23.0.1 ([tools_r23.0.1-linux.zip](https://dl-ssl.google.com/android/repository/tools_r23.0.1-linux.zip "")), but without some files:
    * tools/ant/uibuild.xml
    * tools/apps/
    * tools/lib/emulator/
    * tools/lib/monitor-x86/
    * tools/lib/monitor-x86_64/
    * tools/lib/pc-bios/
    * tools/lib/android.el
    * tools/lib/asm-4.0.jar
    * tools/lib/asm-analysis-4.0.jar
    * tools/lib/asm-tree-4.0.jar
    * tools/lib/asset-studio.jar
    * tools/lib/builder-model.jar
    * tools/lib/build_gradle.template
    * tools/lib/chimpchat.jar
    * tools/lib/ddmlib.jar
    * tools/lib/ddms.jar
    * tools/lib/ddmuilib.jar
    * tools/lib/devices.xml
    * tools/lib/draw9patch.jar
    * tools/lib/ecj-4.2.2.jar
    * tools/lib/emma.jar
    * tools/lib/emma_ant.jar
    * tools/lib/emma_device.jar
    * tools/lib/fat32lib.jar
    * tools/lib/gradle-import.jar
    * tools/lib/hardware-properties.ini
    * tools/lib/hierarchyviewer2.jar
    * tools/lib/hierarchyviewer2lib.jar
    * tools/lib/jcommon-1.0.12.jar
    * tools/lib/jfreechart-1.0.9.jar
    * tools/lib/jfreechart-swt-1.0.9.jar
    * tools/lib/jobb.jar
    * tools/lib/jsilver-1.0.0.jar
    * tools/lib/jython-standalone-2.5.3.jar
    * tools/lib/lib64EGL_translator.so
    * tools/lib/lib64GLES_CM_translator.so
    * tools/lib/lib64GLES_V2_translator.so
    * tools/lib/lib64OpenglRender.so
    * tools/lib/libEGL_translator.so
    * tools/lib/libGLES_CM_translator.so
    * tools/lib/libGLES_V2_translator.so
    * tools/lib/libOpenglRender.so
    * tools/lib/lint.jar
    * tools/lib/lint-api.jar
    * tools/lib/lint-checks.jar
    * tools/lib/lombok-ast-0.2.2.jar
    * tools/lib/monkeyrunner.jar
    * tools/lib/ninepatch.jar
    * tools/lib/rule-api.jar
    * tools/lib/screenshot2.jar
    * tools/lib/sdkstats.jar
    * tools/lib/traceview.jar
    * tools/lib/uiautomatorviewer.jar
    * tools/lib/uibuild.template
    * tools/proguard/
    * tools/support/
    * tools/templates/
    * tools/ddms
    * tools/draw9patch
    * tools/emulator64-arm
    * tools/emulator64-mips
    * tools/emulator64-x86
    * tools/emulator-arm
    * tools/emulator-mips
    * tools/emulator-x86
    * tools/hierarchyviewer
    * tools/jobb
    * tools/lint
    * tools/mksdcard
    * tools/monitor
    * tools/monkeyrunner
    * tools/screenshot2
    * tools/traceview
    * tools/uiautomatorviewer
 2. platform-tools r20 ([platform-tools_r20-linux.zip](https://dl-ssl.google.com/android/repository/platform-tools_r20-linux.zip "")), but without some files:
    * platform-tools/api/
    * platform-tools/systrace/
    * platform-tools/adb
    * platform-tools/dmtracedump
    * platform-tools/etc1tool
    * platform-tools/fastboot
    * platform-tools/hprof-conv
    * platform-tools/sqlite3
 3. build-tools r20.0.0 ([build-tools_r20-linux.zip](https://dl-ssl.google.com/android/repository/build-tools_r20-linux.zip "")), but without some files:
    * build-tools/20.0.0/renderscript/
    * build-tools/20.0.0/aidl
    * build-tools/20.0.0/arm-linux-androideabi-ld
    * build-tools/20.0.0/bcc_compat
    * build-tools/20.0.0/dexdump
    * build-tools/20.0.0/i686-linux-android-ld
    * build-tools/20.0.0/libbcc.so
    * build-tools/20.0.0/libbcinfo.so
    * build-tools/20.0.0/libclang.so
    * build-tools/20.0.0/libLLVM.so
    * build-tools/20.0.0/llvm-rs-cc
    * build-tools/20.0.0/mipsel-linux-android-ld
 4. android-17 r2 ([android-17_r02.zip](https://dl-ssl.google.com/android/repository/android-17_r02.zip "")), but without some files:
    * platforms/android-17/data/
    * platforms/android-17/skins/
    * platforms/android-17/uiautomator.jar
 5. android-19 r3 ([android-19_r03.zip](https://dl-ssl.google.com/android/repository/android-19_r03.zip "")), but without some files:
    * platforms/android-19/data/
    * platforms/android-19/skins/
    * platforms/android-19/uiautomator.jar



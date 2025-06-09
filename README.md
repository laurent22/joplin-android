# joplin-android

Android releases for [Joplin](https://joplinapp.org)

This repository only hosts the Joplin APK files. The source code is at https://github.com/laurent22/joplin and the Google Play page at https://play.google.com/store/apps/details?id=net.cozic.joplin

You should assume that most of these releases are [pre-release](https://joplinapp.org/help/about/prereleases/) unless it is marked as "latest".

## Accessing the releases

GitHub has a "won't fix" bug in the way it sorts releases so don't go to the release page. Instead go to the Tags page as they will be sorted in the correct order:

https://github.com/laurent22/joplin-android/tags

## Choosing the right version

If you do not know your phone's architecture, you can install the version without prefix **joplin-vX.Y.Z.apk** as it includes all the architectures. Otherwise you can find out what architecture your phone is using the following way:

- Install a Terminal app such as **termius**
- Run this command: `adb shell uname -m`

The reply will tell you what architecture the Linux kernel in your Android OS is running. It tells you this in Linux terminology, rather than Android ABI names:

- "aarch64" is "arm64-v8a" ABI.
- "armv7l" is "armeabi-v7a" ABI.
- "x86_64" is "x86_64" ABI.
- "i386" or "i686" is Android's "x86" ABI.

## Changelog

https://joplinapp.org/help/about/changelog/android

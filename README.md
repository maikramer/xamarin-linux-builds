# xamarin-linux-builds
Xamarin Android Linux Builds

## Why?
All i want is share my personal builds, i didn't change anything in code, every change i made was destined to make it build.

## Apis included
API 15 (Android 4.0.4) to API 29 (Android 10)

## Abis included
- armeabi
- v7aarm64
- x86
- x86_64

## Installing
Copy everything to "/usr/lib/xamarin.android/"
Then run:
```sh
sudo ln -s "/usr/lib/xamarin.android/xbuild/Xamarin/Android/" "/usr/lib/mono/xbuild/Xamarin/Android"
sudo ln -s "/usr/lib/xamarin.android/xbuild-frameworks/MonoAndroid/" "/usr/lib/mono/xbuild-frameworks/MonoAndroid"
```

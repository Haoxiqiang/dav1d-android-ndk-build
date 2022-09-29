# dav1d-android-ndk-build

The original code from https://github.com/nova-video-player

## macOS require.
```bash
brew install coreutils
brew install gsed
```
```bash
android dev kits 'ndk;23.1.7779620' 'cmake;3.18.1' 'build-tools;30.0.3'
```
## Build
```bash
./build.sh -a arm64
or
./build_all.sh

if you want use a static library. change build.sh#Line 115 --default-library=static
```

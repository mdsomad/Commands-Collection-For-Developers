## 👇 Build and release an Android app

<br/>
<br/>

### 👇 Build an APK release

```sh
flutter build appbundle
```

## 👇 Build an APK release

```sh
flutter build apk --split-per-abi
```

### 👇 Universal Build an APK release

```sh
flutter build apk
```

## 👇 Update the app's version number

#### The default version number of the app is 1.0.0. To update it, navigate to the pubspec.yaml file and update the following line:

```sh
version: 1.0.0+1
```

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

https://stackoverflow.com/questions/49695393/how-to-build-apk-create-old-version-app-in-flutter

- Run these command

```sh
flutter clean
```

<br/>

- and after that

```sh
flutter build apk --release
```

<br/>

- flutter build appbundle --target-platform android-arm,android-arm64,android-x64

```sh
flutter build appbundle --target-platform android-arm,android-arm64,android-x64
```

<br/>

- This Build Command

```sh
flutter build apk --build-name=1.0.2+1 --build-number=2
```

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

flutter build apk --analyze-size --target-platform android-arm64

flutter build apk --target-platform android-arm,android-arm64,android-x64 --split-per-abi

sudo apt install -f

## 👇 Ubuntu Phone Mirror Commands

adb devices
scrcpy

## 👇 Always on Top Software

sudo apt install wmctrl
https://fostips.com/set-always-on-top-hotkey-ubuntu-20-04/

wmctrl -r :CLASS:"Chrome" -b add,always_on_top

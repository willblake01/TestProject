# Unreal Engine - MacOS

<img alt='Unreal Engine' src='https://dev.epicgames.com/community/api/documentation/image/bafbc878-8d43-4bdd-9964-85d6079d6811?resizing_type=fill&width=1920&height=335' width="100%" />

## Scene Controls

* Thumbstick locomotion (Left controller thumbstick)
* Sprint (Click and hold left thumbstick while moving)
* Snap turn (Right thumbstick L + R)
* Base teleport functionality is unchanged (Right thumbstick up)

## How to use

**Option 1** - Download optimized .sdk file

* [Download the .apk file](https://drive.google.com/file/d/1apvPNiWsgNSHmU8qKQoaU_Ncr1QC7OWA/view?usp=drive_link) and skip to the `Run a project on the Quest 3` section below

**Option 2** - Package in Unreal Engine

* Clone into desired location
* Open `TestProject` project in Unreal Engine
* Run `Platforms > Android > Package Project`
* When packaging completes successfully you can find the optimized build `.apk` file in the `Android_ASTC` directory

*For light building issues on MacOS you will need to add `UnrealEditor` and `UnrealLightmass` to your firewall settings to allow connections or temporarily disable firewall

[Install SDKs with Android Studio Flamingo](https://developer.android.com/studio/releases/past-releases/as-flamingo-release-notes)

## Run a project on the Quest 3

* Install `Meta Quest Developer Hub`
* Connect Quest 3 to machine
* Allow connection from inside the Quest 3 headset
* In the `Meta Quest Developer Hub` navigate to the `Device Manager` tab and locate the `Apps` section. Use the `Add Build` button or drag the .apk file located in `Android_ASTC > TestProject-arm64.apk`

[Getting started with Meta Quest Developer Hub](https://developers.meta.com/horizon/documentation/unity/ts-mqdh-getting-started)

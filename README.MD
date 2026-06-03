# YouTube Music with Morphe Patches (9.17.51)

This repository documents the use of Morphe Patches on YouTube Music version 9.17.51. Morphe Patches provide a set of modifications to enhance the YouTube Music experience by removing ads, enabling background playback, and adding various quality-of-life features.

## Supported Version

- YouTube Music 9.17.51 (experimental support)
- Patch set: Morphe Patches (v1.25.0-dev.11 or later)

## Features

The following patches are available for YouTube Music 9.17.51:

- Ad blocking – removes all audio, video, and banner advertisements.
- Background playback – allows music to continue playing when the screen is off or when using other apps.
- Spoofing – prevents playback errors and buffering by faking the stream to Android VR or Web clients.
- Crossfade – enables smooth transitions between tracks.
- Custom startup page – choose which tab (Home, Explore, Library) opens when the app launches.
- MicroG support – allows login without Google Play Services (useful on de-Googled devices or non-root installations).

## Known Issues

- Personal uploads / user-uploaded music may stop at the 69th second when the "spoof video streams" patch is active. To work around this, disable that specific patch or only apply the spoofing patch for non-personal content.

## Disclaimer

This project is for educational purposes only. Morphe Patches are not affiliated with Google or YouTube. Use at your own risk. The maintainers do not encourage piracy; consider supporting artists by using official premium services when possible.

## References

- Official Morphe Patches repository: [MorpheApp/morphe-patches](https://github.com/MorpheApp/morphe-patches)
- Morphe Builder: [elohim-etz/morphe-builder](https://github.com/elohim-etz/morphe-builder)
- Morphe Documentation: [MorpheApp/morphe-documentation](https://github.com/MorpheApp/morphe-documentation)

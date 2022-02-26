# Examples of configuration files

A few configuration files (.conf) that can be used to analyse bat sounds:

- `Bats_stereo_TEr.conf` : stereo sound file with time expansion x10 on the right channel (e.g. for Pettersson D240x bat detectors)
- `Bats_mono_TE.conf` : mono sound in time expansion x10
- `Bats_mono_FS.conf` : mono sound full spectrum (e.g. for different passive bat detectors such as Audiomoth, Wildlife Acoustics SMx BAT, ...)

These examples are designed to be used on a Mac. To use them on Windows, just change `set wsurf::Info(Prefs,theme) {aqua}` into the default `set wsurf::Info(Prefs,theme) {default}`

Put the configuration files in the following folders:

- Mac: `username\.wavesurfer\1.8\configurations` (hidden folder by default)
- Windows: `C:\Users\user_name\.wavesurfer\1.8\configurations`

## For the standard version

File names with suffix S - standard (BatsS_xxx.conf)

## For the version on this repository

File names with suffix B - bats (BatsB_xxx.conf)



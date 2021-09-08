# deskplayer

deskplayer is an experiment where I attempt to create a cross-platform, light-weight, minimalist, audio player using the Tauri Native Packager (an alternative to electron), and various web technologies. 

# Changelog

please see [`changelog.md`][changelog]

# Development

In order to develop the the code base, we need to run the parcel bundler and the tauri cli in tandem.

First

```bash
yarn start
```
Which will spin up the parcel + tailwindcss, Then

```bash
yarn tauri dev
```

Which will launch the native window
#THIS IS OLD!

Use this instead: https://britzl.github.io/manifestation/



# Defold Appmanifests

A collection of appmanifest files for excluding different parts of the Defold engine which you do not need

To use these files, you must edit your game.project and add the [native_extension] section along with app_manifest specified

```
[native_extension]
app_manifest = /appmanifests/nophysics.appmanifest
```

![game project app manifest](docs/app_manifest_game_project2.png?raw=true "game.project screenshot")

Then you can build or bundle and a version of the engine will be produced with the inclusions / exclusions listed in your appmanifest.

# Included Appmanifests

- headless.appmanifest - headless
- headless_release.appmanifest - headless release
- nophysics_release.appmanifest - no physics, no recording, no profiling
- release.appmanifest - release 
- debug.appmanifest - debug - no exclusions

Todo add more info and compare build sizes


-----

If you make a useful appmanifest please post it as an issue or with a pull request

From this thread: https://forum.defold.com/t/native-extensions/4946/133

More info: https://forum.defold.com/t/native-extensions/4946/138

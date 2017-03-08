DND Character Sheet

## Commands

All commands are run using `npm run` (or `yarn run`).

* `clean` - Deletes the previous build files
* `build` - Compiles and minifies the front-end code
* `build:android` - Build an unsigned android APK
* `build:desktop [platform=all] [arch=all]` - Build desktop executables (available platforms: all, win32, darwin, mas, linux)
* `run:android` - Build and run on android device or emulator
* `start` - Starts the servers (if `NODE_ENV === production`, API server only)

## Build Instructions (From Debian Linux)
### Android
```shell
npm run tauri android build -- --apk
```
`.apk` Location : `<Project_dir>/src-tauri/gen/android/app/build/outputs/apk/universal/release/`
### Windows
```
npm run tauri build -- --runner cargo-xwim --target x86_64-pc-windows-msvc
```
`.exe` Location : `<Project_dir>/src-tauri/target/x86_64-pc-windows-msvc/release/bundle/nsis`
### Linux (Deb, AppImage, rpm)
```
npm run tauri build
````
- `.deb` Location : `<Project_dir>/src-tauri/target/release/bundle/deb/`
- `.AppImage` Location : `<Project_dir>/src-tauri/target/release/bundle/appimage/`
- `.rpm` Location : `<Project_dir>/src-tauri/target/release/bundle/rpm/`

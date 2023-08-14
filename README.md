# Minimal reproduction repo
- Given a webview on a screen of its own with `html` as its source
- When naviagting back the previous screen
- Then, on occassion, it crashes the app without any logs

## Video demo
The crash is around 25 seconds in. for the rest of the time, I am navigating back and forth between a screen with a webview and another one without a webview.

https://github.com/mrzachnugent/react-native-webview-crash-minimal/assets/63797719/d6e8f092-3d20-4f98-839d-3c1ad90e4b1b

### Additional information
I cannot recreate this issue when the source of the webview is a `uri`. It seems to only happend with a source of `html`.

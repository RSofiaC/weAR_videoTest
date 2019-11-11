# weAR_videoTest
Atempt in doing a simple video display using a target with ARjs + Aframe + Unity

## Tech
- [ARjs: to create a web-based AR experience that is non-dependant on installs and work accross platforms] https://github.com/jeromeetienne/AR.js
- [Aframe: to support web-rendered 3D objects + materials for the video display]https://aframe.io/
- [Unity: to be able to create a 3D scene and compile it natively] https://github.com/taylordigital13/ARjs_Unity
- local python server: to serve and try the website

## Tutorial
https://www.youtube.com/watch?v=_WnyC2ZrDls

## Current version (11/11/19)
- Run local server for main folder
```bash 
unityAR.js/ Assets/ AR.js-master/ aframe/ Videotest/ 
```
- show HIRO marker

- Example with Hiro marker runs perfect on Firefox
- unable to run a https local python server (required to try on mobile)
- Safari errors log:
/ Viewport argument key "minimal-ui" not recognized and ignored
/ Unhandled Promise Rejection: [object Event]
/ WebGL: INVALID_VALUE: textImage2D: no video
/ Unhandled Promise Rejection: NotSupportedError: The operation is not supported

## Possible solutions
- [Debug webview] https://github.com/jeromeetienne/AR.js/issues/472
- [Create user interaction] https://github.com/jeromeetienne/AR.js/issues/472
- [Set playsinline] https://aframe.io/docs/0.7.0/introduction/faq.html#why-does-my-video-not-play-on-mobile
- [Set playsinline] https://github.com/aframevr/aframe/issues/316

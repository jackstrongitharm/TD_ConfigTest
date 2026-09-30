# TD Room Configurator (web test)

WebGL build of the Tilbury Douglas room configurator demo, Asset Manager only. Rooms are not part of this repo: they load
from the Unity Asset Manager collection `Configurator/Assets` after **Sign in with Unity** (popup), for accounts with
access to the project. Nothing is stored in the browser.

Built from `TD_RoomPipeline/unity/build_web.ps1` (Unity 6000.6.0f1, WebGL 2, gzip with decompression fallback, so it
serves from GitHub Pages without special headers). `signin-callback.html` is the sign-in return page.

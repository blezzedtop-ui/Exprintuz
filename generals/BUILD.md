# Generals Web build

The public repository must not contain copyrighted Zero Hour game assets.

## Engine
The GitHub Actions workflow `Build GeneralsXWeb WASM` checks out
`meerzulee/GeneralsXWeb@igroteka-wasm`, configures its documented `wasm`
CMake preset and builds `GeneralsXZH.js` + `GeneralsXZH.wasm`.

The output is uploaded as the `generalsxweb-engine` Actions artifact.

## Game data
Users must provide their own legally owned Zero Hour installation. Do not commit
`*.big`, game movies, audio, maps or other EA assets to this repository.

## iPhone target
The launcher remains under `/generals/`. WebGL2 + WebAssembly are checked in
the browser before the engine can be launched.

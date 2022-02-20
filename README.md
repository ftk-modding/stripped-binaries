# For The King stripped binaries

This repository contains stripped version of For The King binaries. All methods/properties/fields are made public with actual code removed. Those binaries may be used when developing mods since Mono will ignore access modifiers check during runtime if `AllowUnsafeBlocks` option is set to `true` for your project.

Generated using [NStrip](https://github.com/BepInEx/NStrip) using following arguments:
`NStrip.exe -p -t ThrowNull .\Assembly-CSharp-firstpass.dll`
`NStrip.exe -p -t ThrowNull .\Assembly-CSharp.dll`

Note: these binaries only includes API and DOES NOT include game logic and therefore are not DMCA-claimable.
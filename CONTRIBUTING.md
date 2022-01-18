## 🔁 Submitting Pull Requests

- before pushing a branch and submitting a PR check other dependency manager's manifests, check podspec for Cocoapods, check Package.swift for SPM if it contains a binary XCFramework.
- if it does and its link is version specific (e.g. like for [Google UMP](https://github.com/AckeeCZ/Bad_iOS_Dependencies/blob/6593bb0227af9ca126b0de243ff946fa13dbf864/GoogleUserMessagingPlatform.json#L2)) 
make sure you use this link
- if none of the above apply, upload binary to [default GH release](https://github.com/AckeeCZ/Bad_iOS_Dependencies/releases/tag/1.0)

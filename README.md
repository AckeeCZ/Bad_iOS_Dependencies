# Bad iOS Dependencies
From time to time we come over a few dependencies, that support only Cococapods or manual integration. We don't like that, so...

This repository will store various JSON files that will provide additional support for binary only libraries, that support only Cocoapods and manual integration.

You can use those JSON by referencing raw JSON in your Cartfile
```
binary "https://raw.githubusercontent.com/AckeeCZ/Bad_iOS_Dependencies/main/Google_Mobile_Ads_SDK.json" ~> 8.9
```

This distribution is **unofficial**.
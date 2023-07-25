# No arquivo settings.json

```json
{
   "dart.flutterSdkPath": ".fvm/flutter_sdk",
   "search.exclude": {
      "**/.fvm": true
   },
   "files.watcherExclude": {
      "**/.fvm": true
   },
   "workbench.colorTheme": "Default Dark Modern"
}
```

---

# No arquivo launch.json

```json
{
   "version": "0.2.0",
   "configurations": [
      {
         "name": "Dev - Debug",
         "request": "launch",
         "type": "dart",
         "flutterMode": "debug",
         "args": ["-t", "lib/main.dart"]
      },
      {
         "name": "Hml - Debug",
         "request": "launch",
         "type": "dart",
         "flutterMode": "debug",
         "args": ["-t", "lib/main_hml.dart"]
      },
      {
         "name": "Prod - Debug",
         "request": "launch",
         "type": "dart",
         "flutterMode": "debug",
         "args": ["-t", "lib/main_prod.dart"]
      },
      {
         "name": "Dev - Iphone",
         "request": "launch",
         "type": "dart",
         "flutterMode": "debug",
         "deviceId": "Johnny",
         "args": ["-t", "lib/main.dart"]
      },
      {
         "name": "Prod - Iphone",
         "request": "launch",
         "type": "dart",
         "flutterMode": "debug",
         "deviceId": "Johnny",
         "args": ["-t", "lib/main_prod.dart"]
      }
   ]
}
```

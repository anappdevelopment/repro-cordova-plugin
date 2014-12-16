# io.repro.cordova

This plugin provides the ability to use [Repro](https://repro.io/)

## Installation

```
cordova plugin add io.repro.cordova
```

### Supported Platforms

- iOS

### Quick Example

```
onDeviceReady: function() {
    app.receivedEvent('deviceready');
    Repro.setUp("YOUR_APP_TOKEN");
    Repro.startRecording();
},
```

For more detail, see http://doc.repro.io/
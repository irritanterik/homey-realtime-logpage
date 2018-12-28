# Realtime Homey Logger and Homey V2 Flow Viewer

Add your local homey ip-address and bearer token in the config.js file and open index.html and flowview.html in a browser.

```
setup = {
  ip: '0.0.0.0',                // Put your ip here or athom cloud uri,
  bearer_token: 'your token',   // Put your V2 bearer token here (i got mine sniffing on app <> homey communications)
  protocol: 'http'              // Change to https if using athom cloud
}
```

### Discover your bearer_token
This tool does not use the new web API with neat authentication. I descovered my token by sniffing traffic between the Homey app and Homey with a packet capture app on an Android device.

### Flow Viewer (flowview.html)
View, search, organize, copy, re-order and test your Homey flows.
![screenshot](https://cloud.githubusercontent.com/assets/15232724/21325455/bda4a3de-c626-11e6-9bbb-29c03f18258f.png)

### Realtime Logger (index.html)
Flow events are only logged during test-runs (started with test-button in flow editor).
NOT WORKING ON HOMEY V2

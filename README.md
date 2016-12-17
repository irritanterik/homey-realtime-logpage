# Realtime Homey Logger and Homey Flow Viewer

Add your local homey ip-address and bearer token in the config.js file and open index.html and flowview.html in a browser.

```
setup = {
  ip: '0.0.0.0',                // Put your ip here or athom cloud uri,
  bearer_token: 'your token',   // Put your bearer token here
  protocol: 'http'              // Change to https if using athom cloud
}
```

Your bearer_token can by found by entering `window.bearer_token` in the browser console while logged in to Homey (open console with F12 in Chrome).

### Notes

Flow events are only logged during test-runs (started with test-button in flow editor).

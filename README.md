# Realtime Homey Logger and Homey Flow Viewer

Add your local homey ip-address and bearer token in the index.html and flowview.html file and open it in a browser.

```
var ip = '0.0.0.0' // Put your ip here
var bearer_token = 'your token' // Put your bearer token here
```

Your bearer_token can by found by entering `window.bearer_token` in the browser console while logged in to Homey (open console with F12 in Chrome).

### Notes

Flow events are only logged during test-runs (started with test-button in flow editor).

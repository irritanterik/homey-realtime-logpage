# Realtime Homey Logger and Homey Flow Viewer

Add your local homey ip-address and bearer token in the config.js file and open index.html and flowview.html in a browser.

```
setup = {
  ip: '0.0.0.0',                // Put your ip here or athom cloud uri,
  bearer_token: 'your token',   // Put your bearer token here
  protocol: 'http'              // Change to https if using athom cloud
}
```

### Discover your bearer_token
Enable the Chrome Console (F12) and open the 'Network' tab. Now open url `http://<your homey IP here>/api/manager/users/user/me` in the browser. Inspect the response and look for something like `Set-Cookie:bearer_token=123verylongnumber456; Path=/; HttpOnly`

### Flow Viewer (flowview.html)
View, search, organize, copy, re-order and test your Homey flows.
![screenshot](https://cloud.githubusercontent.com/assets/15232724/21325455/bda4a3de-c626-11e6-9bbb-29c03f18258f.png)

### Realtime Logger (index.html)

Flow events are only logged during test-runs (started with test-button in flow editor).

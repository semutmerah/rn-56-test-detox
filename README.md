# React Native 0.56.0 test project

This project was created with `react-native init` to test some remaining issues with jest tests.

- Clone this repo
- Change to repo directory
- `yarn`
- `detox build`
- `yarn test`
- `detox test`

*Expected behavior*:

All 3 tests files pass on Mac OS machine and Ubuntu machine

*Actual behavior*:

`yarn test` passes.

`detox test` passes on Mac OS machine (High Sierra 10.13.6)

`detox test` failed on Ubuntu machine (18.04 with kernel 4.15). Error log:

```
detox[12744] ERROR: [EmulatorTelnet.js/TELNET_TIMEOUT] 
detox[12744] ERROR: [index.js/DETOX_INIT_ERROR] 
 Error: response not received
    at Timeout.setTimeout (/home/my_username/Workspace/learn_detox/node_modules/detox/node_modules/telnet-client/lib/index.js:150:47)
    at ontimeout (timers.js:498:11)
    at tryOnTimeout (timers.js:323:5)
    at Timer.listOnTimeout (timers.js:290:5)
```


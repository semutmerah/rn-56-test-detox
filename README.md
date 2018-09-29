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

`detox test` failed on Ubuntu machine


# React Native 0.56.0 test project

This project was created with `react-native init` to test some remaining issues with jest tests.

- Clone this repo
- Change to repo directory
- `yarn`
- `yarn test`
- `detox build`
- `detox test`

*Expected behavior*:

All 3 tests files pass

*Actual behavior*:

`yarn test` passes.

`detox test` fails with the following error:
> Plugin 0 specified in "/.../node_modules/babel-preset-react-native/index.js" provided an invalid property of "default" (While processing preset: "/.../node_modules/babel-preset-react-native/index.js")


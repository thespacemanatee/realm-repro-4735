# Realm Issue #4735 Repro

## Summary

This is a repro project for the issue [#4735](https://github.com/realm/realm-js/issues/4735).

This project is was bootstrapped with `npx crna -t with-dev-client` and `EXPO_BETA=1 expo-cli upgrade` and updated dependencies. The `with-realm` branch includes `realm@11.0.0-rc.1` and should crash on startup while the `without-realm` branch does not include this dependecy and should not crash.

### Note

If the app does not crash on first launch, keep relaunching and it will crash 99% of the time.

## Instructions

```sh
yarn

npx pod-install

yarn ios
```

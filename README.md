# Binding.NewRelic

## Summary

The following binding are for the **NewRelic SDK**.

## Android

Documentation for using the library inside an Android project can be found [here](https://docs.newrelic.com/docs/mobile-monitoring/new-relic-mobile-android/api-guides).

The source for the SDK can be found [here](https://download.newrelic.com/android_agent/ant/). 

The bindings were generated for the version **5.18.1**.


### How to use

Add a reference to the following packages:

- Uno.Binding.NewRelic.Android

#### Permissions
We include the [INTERNET](https://developer.android.com/reference/android/Manifest.permission.html#INTERNET) permission by default as we need it to make network requests:

```
<uses-permission android:name="android.permission.INTERNET"/>
<uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />
```

## iOS

Documentation for using the library inside an iOS project can be found [here](https://docs.newrelic.com/docs/mobile-monitoring/new-relic-mobile-ios/api-guides).

The source for the SDK can be found [here](https://download.newrelic.com/ios_agent). 

The bindings were generated for the version **6.2.0**.

### How to use

Add a reference to the following packages:

- Uno.Binding.NewRelic.iOS

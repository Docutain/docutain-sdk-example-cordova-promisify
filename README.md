# Docutain SDK

## Docutain SDK example app for Cordova

This example app shows how to integrate the [Docutain SDK for Cordova](https://sdk.Docutain.com).

## What is Docutain SDK?

The [Docutain SDK](https://sdk.Docutain.com) brings functionalities for automatic document scanning, data capture, image processing, OCR text recognition, intelligent data extraction, PDF creation and photo payment to your apps.

It works 100% offline, which ensures maximum data safety.

It contains individually licensable modules:
- [Document Scanner SDK](https://sdk.Docutain.com/document-scanner-sdk)
- [OCR SDK for text recognition](https://sdk.Docutain.com/data-capture-sdk)
- [Data Capture and Extraction SDK](https://sdk.Docutain.com/data-capture-sdk)
- [Photo Payment SDK](https://sdk.Docutain.com/fotoueberweisung)

For more details visit our website https://sdk.Docutain.com

If you like to test the functionality without writing any lines of code, check out our [Showcase Apps](https://sdk.docutain.com/#Test).

## Getting started

Clone the repo:

```
git clone https://github.com/Docutain/docutain-sdk-example-cordova
cd docutain-sdk-example-cordova
```

Install the project dependencies:

```
npm install

```

Build on Android

```
cordova platform add android
cordova requirements
cordova build android
```

Run on Android

```
cordova run android --device
```

Build on iOS

```
cordova platform add iOS
cordova requirements
cordova build iOS
```

Run on iOS

```
cd ios
pod install
```

Open the `Docutain_SDK_Example_Cordova.xcworkspace` file from the iOS folder with Xcode.

Set your provisioning and signing settings.

Run the app either in Xcode or via the following command.

```
cordova run iOS --device
```

## Documentation of the Docutain SDK

- [Developer Guide](https://docs.docutain.com/docs/cordova/intro)

## License and Support

The Docutain SDK is a commercial product and requires a paid license for production use. In order to get a trial license, please visit our website via [https://sdk.docutain.com/TrialLicense](https://sdk.docutain.com/TrialLicense?Source=5243146) to generate a trial license key. 

If you need technical support of any kind, please contact us via [support.sdk@Docutain.com](mailto:support.sdk@Docutain.com).






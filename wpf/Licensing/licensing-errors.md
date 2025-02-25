---
layout: post
title: License Key Errors of Essential Studio | Syncfusion 
description: Learn here some information about how to fix Syncfusion license key related errors and more details.
platform: WPF
control: Essential Studio
documentation: ug
---

# Common Licensing Errors

Licensing error popup is displayed with various messages under different circumstances. Here are some ways to resolve different issues.

## License key not registered 

The following error message will be shown if a Syncfusion license key has not been registered in your application. 

**Error message:** This application was built using a trial version of Syncfusion Essential Studio. Please include a valid license to permanently remove this license validation message. You can also obtain a free 30 day evaluation license to temporarily remove this message during the evaluation period. Please refer to this [help topic](https://help.syncfusion.com/wpf/licensing/licensing-errors#license-key-not-registered) for more information.

![License key not registered](licensing-images/licensing-alert.png)

**Solution:** Generate a valid license key from here [Licensed users](https://www.syncfusion.com/account/downloads) or [Trial users](https://www.syncfusion.com/account/manage-trials/downloads) for a specific version and platform.

## Invalid key

If the application is registered with an invalid key, another version of license key, or another platform's license key, the following error message will pop up when launching the application. 

**Error Message:** The included Syncfusion license is invalid. Please refer to this [help topic](https://help.syncfusion.com/wpf/licensing/licensing-errors#invalid-key) for more information.

![License key not registered](licensing-images/invalid-key.png)

**Solution:** Generate a valid license key from here [Licensed users](https://www.syncfusion.com/account/downloads) or [Trial users](https://www.syncfusion.com/account/manage-trials/downloads) for a specific version and platform.

## Trial Expired

The following error message will be shown if the trial key has expired after 30 days.

**Error Message:** Your Syncfusion trial license has expired. Please refer to this [help topic](https://help.syncfusion.com/wpf/licensing/licensing-errors#trial-expired) for more information.

![License key not registered](licensing-images/trial-expired.png)

**Solution:** Purchase from [here](https://www.syncfusion.com/sales/products) to get a valid Syncfusion license.

## Platform Mismatch

If the application is registered with another platform's license key, the following error message will pop up when launching the application.

**Error Message:** The included Syncfusion license is invalid (Platform mismatch). Please refer to this [help topic](https://help.syncfusion.com/wpf/licensing/licensing-errors#platform-mismatch) for more information.

![License key not registered](licensing-images/platform-mismatch.png)

**Solution:** Generate a valid license key from here [Licensed users](https://www.syncfusion.com/account/downloads) or [Trial users](https://www.syncfusion.com/account/manage-trials/downloads) for a specific version and platform.

## Version Mismatch

If the application is registered with another version's license key, the following error message will pop up when launching the application.

**Error Message:** The included Syncfusion license ({Registered Version}) is invalid for version {Required version}. Please refer to this [help topic](https://help.syncfusion.com/wpf/licensing/licensing-errors#version-mismatch) for more information.

![License key not registered](licensing-images/version-mismatch.png)

**Solution:** Generate a valid license key from here [Licensed users](https://www.syncfusion.com/account/downloads) or [Trial users](https://www.syncfusion.com/account/manage-trials/downloads) for a specific version and platform. Kindly follow the [KB](https://www.syncfusion.com/kb/8976/how-to-generate-license-key-for-licensed-products) to generate license key.

## Could not load Syncfusion.Licensing.dll assembly version...?
Make sure that all the referenced Syncfusion assembles are of the same version. Try cleaning and rebuilding the application to resolve assembly conflict issues.









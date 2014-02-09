Android-Device-ID Project
=========================

The Android-Device-ID Project intends to provide freely available ([GPLv3](https://www.gnu.org/licenses/gpl-3.0.html))
XML files for the identification of Android devices.

Contribution
------------

There are three main ways to contribute to the project:

### Option 1:

1. Fork the code.
2. Fill in any missing devices entries you can provide; these must come
   from either a stock device or a stock build.prop.
3. Submit a pull request.

### Option 2:

Submit a new issue with at least the following:
* ro.product.model
* ro.product.brand
* ro.product.name
* ro.product.device
* ro.product.board

When you go this route, please submit a new issue for each device, with the
name of the issue being the device these parameters are for.

### Option 3:

Download 0xD34D's [OpenBuildProp](http://goo.im/devs/0xD34D/OpenBuildProp.apk) application, run on a stock device & submit
the build.prop. Once the build.prop is submitted, you can uninstall the
application.

The source of this application can be found [here](https://github.com/0xD34D/OpenBuildProp).

Additional Notes When Contributing
----------------------------------

* Use the exact values that are contained in the build.prop properties.
* All indentations should be 4 spaces, not a tab.
* If a device has more than one common name (happens often with HTC), use
  the most common name.
* If there are multiple different variants of the ro. values, make a new
  device entry for each one, and note the conflicts in the description.
* Only submit complete device entries.
* If a new manufacture is added to the project, please have the filename
  in upper cae, with a lower case file extension.

Special Thanks to all contributors:
-----------------------------------

Adam Lange, Anup Cowkur, Gunther ART, Markus Guidry, Itzael Martinez, Jacob Soo, Shen Ye, adumont, uberlaggydarwin, civicsiracer06, pylerSM

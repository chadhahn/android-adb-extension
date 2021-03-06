android-adb-extension
==========

Android Debug Bridge extension provides convenient metaclass to execute ADB shell commands.

This gem is useful when working with test automation frameworks like **Calabash-android** and **Appium**.

Installation
==========

In your Gemfile:

`gem 'android-adb-extension'`

Install gem manually:

`$ gem install android-adb-extension`

Tested devices
==========

Current implementation is tested against

> **`Device: HTC One M7`**

> **`SDK: 19`**

> **`Release: 4.4.3`**

Example use cases
==========

Connect your device and enable USB debugging mode

Launch your favorite application which supports portrait and landscape orientations

Launch irb

`$ irb`

Load android-adb-extension

`irb> require 'android-adb-extension'`

Execute `android-adb-extension` commands

SDK version

> **`ADB.sdk`**

Release version

> **`ADB.release`**

Major version

> **`ADB.major`**

Orientation

> **`ADB.orientation`**

> **`ADB.portrait?`**

> **`ADB.landscape?`**

> **`ADB.set_portrait`**

> **`ADB.set_landscape`**

Airplane mode

> **`ADB.airplane_mode`**

> **`ADB.airplane_mode?`**

> **`ADB.enable_airplane_mode`**

> **`ADB.disable_airplane_mode`**

See available methods

> **`ADB.help`**

Did you notice alias methods?

> **`ADB.help`** --> **`ADB.h`**

Run the tests
==========

TODO

License
==========

MIT

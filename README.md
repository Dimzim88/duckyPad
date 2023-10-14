# duckyPad: Do-It-All Mechanical Macropad

[Get duckyPad](https://www.tindie.com/products/21984/) | [Official Discord](https://discord.gg/4sJCBx5) | [Getting Started](getting_started.md) | [Table of Contents](#table-of-contents)

----

duckyPad is a 15-key mechanical macropad that helps **consolidate & speed up workflow** by automating keyboard (and mouse!) inputs. 

![Alt text](resources/pics/title_jpg.jpg)

duckyPad has all the goodies of a high-end mechanical keyboard:

* Mechanical switches
* **Hot-swap**
* **RGB**
* **USB-C**
* Open-source

More crucially, it also features innovations such as:

* **OLED** screen showing what each key does
* Sophisticated **multi-line scripting** with [duckyScript](duckyscript_info.md)
* **32 profiles** of 15 keys, 480 macros total.
* [Automatic profile switching](https://github.com/dekuNukem/duckyPad-profile-autoswitcher) based on active window.
* microSD card storage, move between devices without losing macros.
* No driver needed, works out-of-box on anything that supports USB keyboards.

![Alt text](resources/pics/teaser.gif)

When pressed, each key execute [duckyScript](duckyscript_info.md) to automate keyboard actions.

It can be as simple as shortcuts like `Control + C`, or as complex as launching applications, managing livestreams, or even [creating root backdoors](https://shop.hak5.org/blogs/usb-rubber-ducky/the-3-second-reverse-shell-with-a-usb-rubber-ducky) or [grabbing passwords](https://shop.hak5.org/blogs/usb-rubber-ducky/15-second-password-hack-mr-robot-style). It's all up to you!

## Get a duckyPad!

duckyPad is [now available on Tindie](https://www.tindie.com/products/21984), feel free to grab one there!

And thanks to the interest and support from the [amazing people like you](kickstarter_backers.md), the [Kickstarter campaign](https://www.kickstarter.com/projects/dekunukem/duckypad-do-it-all-mechanical-macropad) has been a great success!

## Join Our Discord!

Feel free to join our [Official Discord](https://discord.gg/4sJCBx5) for discussions, questions, sharing scripts, and latest updates!

## Highlights

* 15 Mechanical Switches
* **`Hot-Swap`** Sockets
* Per-Key **`RGB Lighting`** 
* **`OLED Screen`** showing profile and key names.
* Powerful multi-line scripting with [duckyScript](duckyscript_info.md)
* 32 profiles of 15 keys, 480 macros total.
* [Automatic profile switching](https://github.com/dekuNukem/duckyPad-profile-autoswitcher) based on active window
* microSD storage
* USB-C Connector
* Works with all major OSs, no driver needed.
* Multiple keyboard layouts (French, Belgium, German, Dvorak, etc)
* Fully Open Source!

## Showcase

By **`automating frequently-used actions with duckyPad`**, you can streamline and speed up your everyday routine.

Here are a few examples:

### Launching Applications  

You can set up duckyPad to open your favourite app with the press of a button: 

![Alt text](resources/pics/winapps.gif)

### Managing Livestreams 

With the press of a key, you can switch scenes, start/stop stream, start/stop recording, play ads, and a lot more!

![Alt text](resources/pics/obs.gif)

### Security Research

With the ability to automate keyboard inputs, it is possible to take over an entire computer with the push of a button.

This is known as [BadUSB attack](https://arstechnica.com/information-technology/2014/07/this-thumbdrive-hacks-computers-badusb-exploit-makes-devices-turn-evil/), and it was the original purpose of [USB Rubber Ducky](https://shop.hak5.org/products/usb-rubber-ducky-deluxe).

But of course, it's up to you to decide what to do!

![Alt text](resources/pics/badusb.gif)

### Photoshop / CAD 

You can put all your shortcuts in one place, resulting in a more efficient workflow: 

![Alt text](resources/pics/cad.gif)

### One-finger Twitch Chat

![Alt text](resources/pics/twitch.gif)

### Switching Profiles

With all the potential usages, duckyPad supports up to 32 profiles.

Simply press the +/- button to switch between them, or use the [profile autoswitcher](https://github.com/dekuNukem/duckyPad-profile-autoswitcher) to **switch automatically** based on **current active window**.

![Alt text](resources/pics/profiles.gif)

### ... and more!

Those are just some examples! You can use duckyPad to do whatever **`you`** want!

## Features

### Mechanical Switches

duckyPad is compatible with Cherry MX-style mechanical switches (3 or 5-pin).

duckyPad comes with **`Gateron Green`** or **`Kalih BOX Navy`** switches, both of which are firm and clicky.

Of course, you can also install your own switches!

### Keycaps

By default, duckyPad comes with blank translucent ABS R4 keycaps:

![Alt text](resources/pics/caps.jpg)

Of course, you can also install your own!

### Hot-swap Sockets

duckyPad supports hot-swapping with Kailh sockets.

You can install/remove the switches by hand, **`no soldering needed`**.

![Alt text](resources/pics/hotswap.gif)

### Per-key RGB backlight

Each key on duckyPad has its own RGB backlight. You can assign unique colours to suit your needs.

### OLED screen

duckyPad has an OLED screen. It displays current **`profile and key names`**, so you know what each key does at a glance.

* 1.3-inch blue OLED display
* High contrast with true OLED black
* 128 x 64 resolution
* Burn-in prevention

![Alt text](resources/pics/oled_closeup.jpg)

### duckyScript

duckyPad uses [duckyScript](duckyscript_info.md) for keyboard automation. It was originally developed for [USB Rubber Ducky](https://shop.hak5.org/products/usb-rubber-ducky-deluxe).

duckyScript is powerful but also easy and straightforward to write.

A simple example look like this:

`CONTROL SHIFT ESC`

Now when you press a key on duckyPad, it will bring up the Task Manager, no need for memorising and pressing a 3-key combo.

![Alt text](resources/pics/task.gif)

Of course, duckyScript can do much more!

Here is a more complex multi-line example that open up notepad, types "Hello world", and increases text size:

```
WINDOWS R
DELAY 400
STRING notepad
ENTER
DELAY 400

STRING Hello World!
CONTROL +
REPEAT 10
```

![Alt text](resources/pics/hello.gif)

### Companion App

duckyPad comes with a companion app for Windows 10, macOS, and Linux. You can use it to:

* Manage profiles
* Manage key names, colours, and arrangements.
* Write, debug, and test-run duckyScript.
* Change, save, and backup configurations.

![Alt text](resources/pics/pcapp.png)

But more importantly, duckyPad app **`respects your privacy`**:

* Fully open-source
* No need to create an account
* No data collection whatsoever
* No internet connection required
* You don’t even have to use it! You can [set up your duckyPad manually](./manual_setup.md).

### USB-C and Device Compatibility

duckyPad uses USB-C connector for maximum device compatibility.

![Alt text](resources/pics/usbc.jpg)

You can use duckyPad out-of-box on pretty much anything that supports USB keyboards, **`no driver needed`**. Examples include:

* PC
* Mac
* Linux
* Raspberry Pi
* iPhone / iPad
* Android phones and tablets
* Chromebooks
* Game consoles

duckyPad’s firmware can also be [easily updated via USB-C](firmware_updates_and_version_history.md) for new features and bug fixes.

### Keyboard Layouts

duckyPad supports multiple keyboard layouts:

* English (US)
* French
* Belgium
* German
* Dvorak
* ...and more [user-created](keymap_instructions.md) layouts!

### Dimensions

[Click me](pcb/plates) for vector files of front and back plates.

[Click me](resources/pics/dimensions.png) for dimensions drawings.

## I want one!

duckyPad is [now available on Tindie!](https://www.tindie.com/products/21984), feel free to grab one there!

Also consider [joining our discord](https://discord.gg/4sJCBx5) for latest updates and discussions.

## Press Kit / More Photos

[Click me](https://drive.google.com/drive/folders/1unbhvTEYcIKlmMEPPsL88o1tNOvzpQyo?usp=sharing) to download some high-resolution photos of duckyPad, feel free to share them.

## Getting started

Please see [the instruction manual](./getting_started.md) on how to use your duckyPad.

## Making one yourself

Please see [this guide](./build_it_yourself.md).

## Derivatives

A number of projects are based on duckyPad, they are listed here!

* simonCor ported this project to a [STM32F4 black pill](https://github.com/simonCor/poor-mans-ducky-pad), with hand-soldered connections and 3D-printed case, very neat!

* headslash is working on [Frankenduck](https://github.com/headslash/Frankenduck), with redesigned PCB, 3D-printed case, and extra switches.

## Table of Contents

[Main page](README.md)

[Getting Started Guide](getting_started.md)

[Kit Assembly Guide](kit_assembly_guide.md)

[Using duckyScript](duckyscript_info.md) | [duckyScript 3 Info](duckyscript3_instructions.md)

[Common issues / Troubleshooting](troubleshooting.md)

[Firmware Updates and Version History](firmware_updates_and_version_history.md)

[Make Your Own Keymap](./keymap_instructions.md)

[Build a duckyPad Yourself](build_it_yourself.md)

[Kickstarter Backer Acknowledgments](kickstarter_backers.md)

## Questions or Comments?

Please feel free to [open an issue](https://github.com/dekuNukem/duckypad/issues), ask in the [official duckyPad discord](https://discord.gg/4sJCBx5), DM me on discord `dekuNukem#6998`, or email `dekuNukem`@`gmail`.`com` for inquires.

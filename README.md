![CI Status](https://github.com/agronick/aa-torque/actions/workflows/ci.yml/badge.svg?branch=master)
![downloads](https://img.shields.io/github/downloads/agronick/aa-torque/total.svg)


# Torque Plugin for Android Auto 

This is a performance monitor based on [Chillout's Performance Monitor](https://github.com/jilleb/mqb-pm) which was based on Martoreto's aa-stats.
The app has been modified with a focus on making it more customizable with the ability
to obtain any PID from Torque. Torque pro is required to use this app.

The original app focused on VAG (Volkswagen Auto Group) cars. This version focuses on exposing
all data from Torque in a way that is as customizable as possible.

## Help and helping
- Visit [the dicussions page](https://github.com/agronick/aa-torque/discussions) to ask questions and get support
- English isn't your native language? [Help translate this app!](https://poeditor.com/join/project/yttme0y1VZ). Many of the translations are incomplete.
- Help spread the word. Make posts on forums and other social networks showing off your setup.
- This app is taking hundreds of hours of work. If you enjoy it consider donating on [Paypal](https://www.paypal.me/kagronick) or [Github Sponsors](https://github.com/agronick).

# Main features:
- Display data from Torque including custom PIDs
- Many themes, fonts, incons, and backgrounds to choose from
- Up to 10 dashboards
- Rotary dial support
- Supports custom expressions using [EvalEx](https://ezylang.github.io/EvalEx/references/functions.html)
- Backup, restore, and share your configuration

# Instructions:


## Prepare
- Download the latest [release](https://github.com/agronick/aa-torque/releases).
- Install [Torque Pro](https://play.google.com/store/apps/details?id=org.prowl.torque&hl=en_US&gl=US)
- Make sure Android Auto is in developer mode: Open Android Auto (while not connected to the car), go to About. Tap the "About Android Auto" header 10 times until you see a toast message saying you're a developer. From the right top corner select developer options, scroll down and make sure you check "Unknown sources". This will allow programs from non-Playstore apps to be run on Android Auto. See a picture guide how to enable Developer mode here: https://www.howtogeek.com/271132/how-to-enable-developer-settings-on-android-auto/

## Install
- Install the APK that you downloaded in the _Prepare_ section using your normal package installer
- Open _AA Torque Settings_
- Select the options menu and select force update. Follow the process so your phone will reinstall it thinking it came from the Play Store.
- If this fails, you can try using [Kingstaller](https://github.com/fcaronte/KingInstaller/releases) so your phone thinks it came from the Play Store. Reference the Kingstaller README if you have issues installing. 

Note: Do not open a bug for an installation issue. This is a hack and may take time and effort in order to get it to work. I can not troubleshoot every phone. Pixel phones have special instructions on the Kingstaller page. There seems to be issues with Android 14 which may be able to be bypassed with root.

## Using
- Open the AA Torque settings, grant all the rights it's requesting. If you don't do this, the app will NOT work.
- Hook your phone to your car's USB, start Android Auto on your unit.
- You can find the AA Torque in the menu on the lower right in Android Auto, the one with the dashboard clock on it.

# Screenshots:
Some screenshots of the app:

![278239030-0d8ded34-9528-48db-a285-e81e4b849717](https://github.com/agronick/aa-torque/assets/2042303/e31b0598-25ec-4003-bcee-11e5e108d3a4)

![chat_view](https://github.com/agronick/aa-torque/assets/2042303/a99571f9-0bb3-43ec-89ce-938e41506e97)
New chart view!

![Screenshot_20231002_130401](https://github.com/agronick/aa-torque/assets/2042303/229315c8-ad3b-42e6-86e6-e7fe7abb16a8)

![Screenshot_20231002_130452](https://github.com/agronick/aa-torque/assets/2042303/698c666b-5e3c-4611-80a5-8e767b04186a)

![20231001-162619](https://github.com/agronick/aa-torque/assets/2042303/1b07b67b-d4bc-41e8-8235-a1418ee37bfe)

![c3c3yrxj11sb1](https://github.com/agronick/aa-torque/assets/2042303/171359f3-1abe-4808-85fb-588dfe1194b6)

![rx2ohmzjsirb1](https://github.com/agronick/aa-torque/assets/2042303/52c83a91-c3b6-430e-967a-4473fc51e51e)

![a](https://user-images.githubusercontent.com/147246549/273383355-63414b98-c333-4760-8e71-772ba823d65b.png)


## Custom Expressions
AA Torque uses [EvalEx](https://ezylang.github.io/EvalEx) for custom expressions. You can find documentation [here](https://ezylang.github.io/EvalEx/references/functions.html).

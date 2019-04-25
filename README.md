
# Switch-SD

To help keep your Nintendo Switch's SD cards up to date with homebrew

## Getting Started

These instructions will help you get your Nintendo Switch's SD cards setup properly for running homebrew applications. It is never recommended to use this repository as your main source of the latest homebrew developments, only as an accessory to help keep your SD card updated. It is always recommended to follow [Plailect's Switch Hacks Guide](https://switch.hacks.guide) to understand what files are being placed onto your SD card and what each file is for, ensuring you know how to use them and whether or not you want them.

### Prerequisites

1. An SD card formatted as FAT32 or exFAT, preferably the one that came with your Nintendo Switch
2. A proper installation of [git](https://git-scm.com) on the device you will use to update your SD card
3. Patience if you have slow internet

### Installing

0. Read [Plailect's Switch Hacks Guide](https://switch.hacks.guide) to understand what new files you will be placing on your Nintendo Switch's SD card
1. Insert your SD card into your device with the git tools
2. Open a terminal and navigate to the root of your SD card
3. Run the following commands:
- Initialize an empty git repository
```
$ git init
```
- Set the origin of the repository to Switch-SD
```
$ git remote add origin https://github.com/JoshuaDoes/Switch-SD.git
```
- Pull from the origin's master branch
```
$ git pull origin master
```
- Set the repository's upstream to the origin's master branch
```
$ git branch --set-upstream-to=origin/master
```
4. Eject your SD card from your device and insert it into your Nintendo Switch
5. Profit!

### Updating

0. Read [Plailect's Switch Hacks Guide](https://switch.hacks.guide) to understand what new files you will be placing on your Nintendo Switch's SD card
1. Insert your SD card into your device with the git tools
2. Open a terminal and navigate to the root of your SD card
3. Run the following command:
- Pull the latest changes from the Switch-SD repository
```
$ git pull
```
4. Eject your SD card from your device and insert it into your Nintendo Switch
5. Profit!

## Contributing

Make a pull request with a detailed description of what your commits will bring to the [Switch-SD](https://github.com/JoshuaDoes/Switch-SD) repository!

## Credits & Acknowledgements

- [CTCaer](https://github.com/CTCaer) for [Hekate](https://github.com/CTCaer/Hekate)
- [switchbrew](https://github.com/switchbrew) for [Atmosphère](https://github.com/Atmosphere-NX/Atmosphere)
- [shchmue](https://github.com/shchmue) for [Lockpick_RCM](https://github.com/shchmue/Lockpick_RCM)
- [FlagBrew](https://github.com/FlagBrew) for [Checkpoint](https://github.com/FlagBrew/Checkpoint)
- [mtheall](https://github.com/mtheall) for [FTPD](https://github.com/mtheall/ftpd)
- [exelix11](https://github.com/exelix11) for [NXThemeInstaller](https://github.com/exelix11/SwitchThemeInjector)
- [joel16](https://github.com/joel16) for [NX-Shell](https://github.com/joel16/NX-Shell)
- [vgmoose](https://github.com/vgmoose) for [hbappstore](https://github.com/vgmoose/hb-appstore)
- [Plailect](https://github.com/Plailect) for [Switch Hacks Guide](https://switch.hacks.guide)
- [Nintendo Homebrew](https://github.com/nh-server) for [NH Switch Guide](https://nh-server.github.io)

## License

This project maintains no licensing, except that you must adhere to the licensing of all included projects (as credited above).

## Donations

All donations are highly appreciated. They are not necessary, but they definitely help me to keep focus on the little projects like these for those who wish to keep them actively updated.

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://paypal.me/JoshuaDoes)
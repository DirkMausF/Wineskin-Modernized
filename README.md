<a href="https://github.com/DirkMausF/wineskin-new/"><img src="https://github.com/DirkMausF/wineskin-new/blob/master/wineskin.png" height="250" width="250" ></a>

# Wineskin New

**Wineskin New** is a refubished version of a user-friendly tool used to make ports of Microsoft Windows software to Apple's macOS.

Originally developed by urgesoftware.com, the original project is not maintained anymore. So we decided to reanimate it.

This project mainly consists of source from [Unoffical_Wineskin](https://github.com/vitor251093/wineskin/commits/Unoffical_Wineskin/), [The-Wineskin-Project](https://github.com/The-Wineskin-Project/wineskin-source/) and [Gcenx/WineskinServer](https://github.com/Gcenx/WineskinServer/).

**You are welcome to contribute, making Wineskin a better solution! ;)**


## How Does It Work?

> The ports are in the form of normal macOS application bundle wrappers.
> It works like a wrapper around the Windows software, and you can share just the wrappers if you choose.
> 
> Make ports/wrappers to share with others, make ports of your own open source, free, or commercial software, or just make a port for yourself!
> Why install and use Windows if you don’t need to?

Wineskin relies on [WINE](http://www.winehq.org/) ("WINE Is Not an Emulator") under the hood:

> Instead of simulating internal Windows logic like a virtual machine or emulator,
> Wine translates Windows API calls into POSIX calls on-the-fly,
> eliminating the performance and memory penalties of other methods
> and allowing you to cleanly integrate Windows applications into your desktop.

## Quick Start

Clone the repository and build the dependencies:

```bash
$ https://github.com/DirkMausF/wineskin-new/
$ cd wineskin_new/
$ carthage update
```

Open `Wineskin.xcworkspace` in Xcode and build:

```bash
$ open Wineskin.xcworkspace
```

Or build via the command line:

```bash
$ xcodebuild -workspace Wineskin.xcworkspace -scheme Wineskin build
$ xcodebuild -workspace Wineskin.xcworkspace -scheme "Wineskin Winery" build
$ xcodebuild -workspace Wineskin.xcworkspace -scheme WineskinLauncher build
```

## Licensing

The license is kept the same as the original material as LGPL 2.1.
You can find more details in the [LICENSE](LICENSE) file.

## Credits

[Original website, offline](http://wineskin.urgesoftware.com/)
 
[Wineskin original code](https://sourceforge.net/projects/wineskin/)

[Unoffical_Wineskin](https://github.com/vitor251093/wineskin/commits/Unoffical_Wineskin/)

[The-Wineskin-Project](https://github.com/The-Wineskin-Project/wineskin-source/)

[Gcenx/WineskinServer](https://github.com/Gcenx/WineskinServer/)

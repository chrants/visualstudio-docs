---
title: "Install Visual Studio 2019 for Mac"
description: "Instructions on how to install Visual Studio 2019 for Mac and additional components required for cross-platform development."
author: conceptdev
ms.author: crdun
ms.date: 04/02/2019
ms.technology: vs-ide-install
ms.assetid: 22B1F2CD-32AE-464D-80AC-C8AB4786B015
ms.custom: video
---
# Install Visual Studio 2019 for Mac

To start developing native, cross-platform .NET apps on macOS, install Visual Studio 2019 for Mac following the steps below.

 > [!div class="button"]
 > [Download Visual Studio for Mac](https://visualstudio.microsoft.com/downloads/?utm_medium=microsoft&utm_source=docs.microsoft.com&utm_campaign=navigation+cta&utm_content=download+vsmac2019)

## Requirements

- A Mac with macOS High Sierra 10.12 or above.

To build Xamarin apps for iOS or macOS, you'll also need:

- Xcode 10.0 or above. The latest stable version is usually recommended.
- An Apple ID. If you don't have an Apple ID already you can create a new one at https://appleid.apple.com. It's necessary to have an Apple ID for installing and signing into Xcode.

## Installation instructions

1. Download the installer from the [Visual Studio for Mac download page](https://aka.ms/vsmac).
2. Once the download is complete, click the **VisualStudioforMacInstaller.dmg** to mount the installer, then run it by double-clicking the arrow logo:

    [![Click the large arrow to begin installation](media/install-installer-sml.png)](media/install-installer.png#lightbox)

3. You may be presented with a warning about the application being downloaded from the Internet. Click **Open**.
4. Wait while the installer checks your system:

    [![The installer checks your system for installed components](media/install-checking-sml.png)](media/install-checking.png#lightbox)

5. An alert will appear asking you to acknowledge the privacy and license terms. Follow the links to read them, then press **Continue** if you agree:

    [![Follow the links to the privacy and terms, then continue if you agree](media/install-privacy-sml.png)](media/install-privacy.png#lightbox)

6. The list of available workloads is displayed. Select the components you wish to use:

    [![Choose which optional workload features you would like to install](media/install-selection.png)](media/install-selection.png#lightbox)

   If you do not wish to install all platforms, use the guide below to help you decide which platforms to install:

   * **Apps using Xamarin**:
      - Xamarin.Forms – Select **Android** and **iOS** platforms.
      - iOS only – Select **iOS** platform (Note that you will need to install [**Xcode**](https://developer.apple.com/xcode/)).
      - Android only – Select **Android** platform (Note that you should also select the relevant dependencies).
      - Mac only – Select **macOS** platform (Note that you will need to install [**Xcode**](https://developer.apple.com/xcode/)).
      - Fully cross-platform Xamarin apps – Select **Android**, **iOS**, and **macOS** platforms.
   * **.NET Core applications** – Select **.NET Core** platform.
   * **ASP.NET Core Web Applications** – Select **.NET Core** platform.
   * **Cross-platform Unity Game Development** – No additional platforms need to be installed beyond Visual Studio for Mac. Refer to the [Unity setup guide](/visualstudio/mac/setup-vsmac-tools-unity) for more information on installing the Unity extension.

7. After you have made your selections, press the **Install** button.
8. The installer will display progress as it downloads and installs Visual Studio for Mac and the selected workloads. You might be prompted to enter your password to grant the privileges necessary for installation.

If you have network trouble while installing in a corporate environment, review the [installing behind a firewall or proxy](https://docs.microsoft.com/visualstudio/mac/installation#install-visual-studio-for-mac-behind-a-firewall-or-proxy-server) instructions.

Learn more about the changes in the [release notes](https://docs.microsoft.com/visualstudio/releasenotes/vs2019-mac-relnotes).

> [!NOTE]
> If you chose not to install a platform or tool during the original installation (by unselecting it in step #6), you must run the installer again if you wish to add the components later.

## Install Visual Studio for Mac behind a firewall or proxy server

To install Visual Studio for Mac behind a firewall, certain endpoints must be made accessible in order to allow downloads of the required tools and updates for your software.

Configure your network to allow access to the following locations:

- [Visual Studio endpoints](/visualstudio/install/install-visual-studio-behind-a-firewall-or-proxy-server)

## Next steps

Installing Visual Studio for Mac allows you to start writing code for your apps. The following guides are provided to guide you through the next steps of writing and deploying your projects.

### iOS

1. [Hello, iOS](https://developer.xamarin.com/guides/ios/getting_started/hello,_iOS/)
2. [Device Provisioning](https://developer.xamarin.com/guides/ios/getting_started/installation/device_provisioning)(To run your application on device).

### Android

1. [Using the Xamarin Android SDK Manager](https://developer.xamarin.com/guides/android/getting_started/installation/android-sdk/?ide=xs)
2. [Android SDK Emulator](https://developer.xamarin.com/guides/android/getting_started/installation/android-emulator/)
4. [Set Up Device for Development](https://developer.xamarin.com/guides/android/getting_started/installation/set_up_device_for_development/)

### .NET Core apps, ASP.NET Core web apps, Unity game development

For other Workloads, refer to the [Workloads](workloads.md) page.

## Related Video

> [!Video https://channel9.msdn.com/Shows/Visual-Studio-Toolbox/Visual-Studio-for-Mac-Acquisition/player]

## See also

- [Install Visual Studio (on Windows)](/visualstudio/install/install-visual-studio)

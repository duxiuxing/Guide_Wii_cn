# Priiloader Usage

Priiloader 能够在 Wii 的系统菜单启动之前加载，以此得名：Pre Loader。玩家在修改游戏主机的时候，错误的操作会导致设备因软件故障而无法启动，如同砖块一样无用，这种情况被形象地称之为：**变砖（Brick）**。而 Priiloader 最为人熟知的功能就是：**防砖、救砖**，就冲这一点，你就应该把它视为 Wii 的必装 App。

Priiloader 包含了各种能够增强、解锁和修复系统菜单的功能。甚至还可以修改 Wii 的默认启动设置，跳过系统菜单，开机直接启动指定的自制软件。

本文记录了 Priiloader 上的那些可能对你有用的功能特性。


## System Menu Hacks（破解系统菜单）

Priiloader has a large selection of options that, once enabled, change the behaviour of the Wii to one of your choice. You can find more information on each hack on the [Priiloader hacks list](https://dacotaco.github.io/priiloader/docs/HACKSLIST.html). Additionally, you can visit the [Priiloader FAQ](https://dacotaco.github.io/priiloader/docs/FAQ.html) which has more relevant information regarding System Menu hacks.

## Additional options

These are some extra things you can do with Priiloader to enhance your homebrew experience. This is optional.

### Autobooting with Priiloader

Priiloader allows you to automatically boot to the Homebrew Channel, an individual homebrew application, or Priiloader itself. This is optional.

#### Autobooting a Homebrew application

::: warning

If you would like to autoboot USB loader GX, do this first:

* Download the USB Loader GX forwarder WAD ([Wii](https://github.com/wiidev/usbloadergx/raw/updates/USBLoaderGX_forwarder%5BUNEO%5D_Wii.wad), [vWii](https://github.com/wiidev/usbloadergx/raw/updates/USBLoaderGX_forwarder%5BUNEO%5D_vWii.wad)).
* Download the [UNEO Channel Booter for Priiloader](https://sourceforge.net/projects/usbloadergx/files/Releases/Forwarders%20dols/UNEO%20Channel%20Booter%20for%20Priiloader.zip/download).
* Install the forwarder WAD with a WAD manager like [YAWM ModMii Edition](yawmme).
* Extract the `UNEO Channel Booter for Priiloader.zip` file anywhere.
* Copy `uneoboot.dol` to the root of your SD card.

You will be installing `uneoboot.dol` in step 3.

:::

1. Launch the Homebrew Channel
1. Launch Load Priiloader from the list of homebrew.
1. Scroll down to `Load/Install file` and press A.

    ![](/images/priiloader/menu_install_file.png)

1. Scroll through the menu until your desired homebrew app is highlighted, and press A to install it.

    ![](/images/priiloader/installing_file.png)

    ![](/images/priiloader/installing_file_ok.png)

1. Press `B` to return to the main menu.
1. Scroll down to `Settings` and press A.

    ![](/images/priiloader/menu_settings.png)

1. Press Right to cycle through the Autoboot options until the `Installed file` option is selected.

    ![](/images/priiloader/autoboot_installed_file.png)

1. Scroll down to `save settings` and press A.

    ![](/images/priiloader/settings_save.png)

1. Press `B` to return to the main menu.
1. Scroll back up to `System Menu` and press A.

Your Wii should now automatically boot to whichever homebrew app you installed.

#### Autobooting the Homebrew Channel or Priiloader

1. Launch the Homebrew Channel
1. Launch Load Priiloader from the list of homebrew.
1. Scroll down to `Settings` and press A.

    ![](/images/priiloader/menu_settings.png)

1. Press Right to cycle through the Autoboot options until your desired option is selected.
    * Disabled` will autoboot to the Priiloader menu.

    ::: warning

    Please don't set Autoboot to `BootMii IOS`. You will get stuck in a loop until you continuously hold the RESET button to enter the Priiloader menu.

    :::

    ![](/images/priiloader/autoboot_disabled.png)

1. Scroll down to `save settings` and press A.

    ![](/images/priiloader/settings_save.png)

1. Press `B` to return to the main menu.
1. Scroll back up to `System Menu` and press A.

---

::: tip

[Click here to return to the main Priiloader guide.](priiloader)

:::

---

::: tip

[Click here to go back to the site index.](site-navigation)

:::

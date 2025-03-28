---
title: Adding Updates
description: Adding OPT updates to the game data.
---

The game adds new content through OPT or option updates. These updates will be released periodically and will contain new songs, events, and other content.

Before release version 250228.1208, only the base game (A000) was supported. However, support for other option updates was added in this version.

Please note that only official updates are tested. They are: A000 (base game), A005, A011, A021, A022.

If you are still playing the old versions, please do not merge the contents of the update files directly into A000, as this will cause the game to load data abnormally.

## Adding Options

To add an option, you can follow these steps:

### Directly update on device

1. Download the option archive on your mobile device.
2. Unzip the archive and copy the Axxx folder to the `StreamingAssets` folder, next to A000.  
   * Android: `/sdcard/Android/data/app.KanadeDX/files/KanadeDX/StreamingAssets`.
   * iOS: Files app > On My iPad > KanadeDX > StreamingAssets.
3. Open KanadeDX version 250228.1208 or later.
4. Before entering, click on the settings icon in the top right corner.
5. Scroll down, click on "Manually reinitialize all AssetBundles", and start converting.

### Update through PC

1. Download the option archive on your computer.
2. Unzip the archive and copy the Axxx folder to an empty folder, and place the Miniserve executable and [this Python script](/misc/scripts/tree.py) in the same directory.
3. Run `python tree.py` in the command line, it will generate a `tree.csv` file in the current directory.
4. Start Miniserve.
5. Open KanadeDX version 250228.1208 or later.
6. Click on the settings icon in the top right corner, scroll down, and click on "Manually re-download the resources".
7. Enter the Miniserve URL and start downloading.
8. After the download is complete, restart KanadeDX, go back to settings, click on "Manually reinitialize all AssetBundles", and start converting.

> If you are updating from an older version of KanadeDX, this process will recheck all asset bundles in A000 as well. However, this is a one-time process, future updates will no longer process files that have been processed before.

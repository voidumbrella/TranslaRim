![Header](./header.png)

# TranslaRIM
This is an unofficial English patch for Trickal Re:vive.
It's pronounced like "translating" with the last syllable replaced with the best Ghost of the game.

## Installation
Only Android devices are supported.

You need some way to access the `Android/data` folder on your device.
Thankfully, you do NOT need to root your device for this, but Android thinks all users are idiots and prevent you from touching anything system related.
Feel free to research your own ways to do this.
Using [Android Debug Bridge](https://developer.android.com/tools/releases/platform-tools) command line tools to push the files is a possibility.
If terminals are too scary for you, [ADB Explorer](https://github.com/Alex4SSB/ADB-Explorer) offers a graphical interface for ADB.

Some people on the Internet report that [Shizuku](https://play.google.com/store/apps/details?id=moe.shizuku.privileged.api) is an app
that can help you get access without connecting to a separate computer.
Have not tried this myself and you'd need to do your own research on that.

Once you figure out a way to write to this folder through your method of choice:
1. Download the latest `patched_kr.client` file from [Github Releases](https://github.com/voidumbrella/TranslaRim/releases)
2. Locate the `Android/data/com.epidgames.trickcalrevive/files/Packages/tables` folder.
3. (Optional) Make a backup of any files you are replacing below.
4. Overwrite the `kr.client` file with the patched version you downloaded.

If the patch somehow breaks the game, the game will still boot but hang on the initial splash screen.
You can then redownload all the data files from the upper right button.

## Can this get me banned?
This only modifies a couple of resource files that contain nothing but text.
It does not (and I don't have the skills to) modify the game client itself or other data in any way.
I don't think in the history of all gacha games anyone has been banned for doing something like this.

Note that detecting the resource files have been tampered with is trivial, so if EpidGames *really* wanted to, they could ban you for this.
Mostly saying this to cover my ass and I highly doubt they would do something like that.

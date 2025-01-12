![Header](./header.png)

# TranslaRIM
This is an unofficial English patch for Trickal Re:VIVE.
It's pronounced like "translating" with the last syllable replaced with the best Ghost of the game.

## Disclaimer
At this moment, the patch is largely incomplete, barely proofread, and written by someone fluent in zero languages.
Any suggestions/criticisms/reports of mistakes are welcome.

There is currently no plan to translate the story.

## Installation
Only Android devices are supported.
I don't own any iOS devices so I have no idea if any of these below steps are possible without jailbreak.
Please let me know if you do figure it out.

You need some way to access the `Android/data` folder on your device.
Thankfully, you do NOT need to root your device for this, but Android thinks all users are idiots and prevent you from touching anything system related.
Feel free to research your own ways to do this.
Using [Android Debug Bridge](https://developer.android.com/tools/releases/platform-tools) command line tools to push the files is a possibility.
If terminals are too scary for you, [ADB Explorer](https://github.com/Alex4SSB/ADB-Explorer) offers a graphical interface for ADB.

I've also had success with FV File Manager which seems to work without any hassle.

Once you figure out a way to write to this folder through your method of choice:
1. Download the latest files from [Github Releases](https://github.com/voidumbrella/TranslaRim/releases)
2. Locate the `Android/data/com.epidgames.trickcalrevive/files/Packages/tables` folder.
3. (Optional) Make a backup of any files you are replacing below.
4. Overwrite any files with patched versions you downloaded.

If the patch somehow breaks the game, the game will still boot but hang on the initial splash screen.
You can then redownload all the data files from the upper right button.

## Can this get me banned?
This only modifies a couple of resource files that contain nothing but text.
It does not (and I don't have the skills to) modify the game client itself or other data in any way.
I don't think in the history of all gacha games anyone has been banned for doing something like this.

Note that detecting the resource files have been tampered with is trivial, so if EpidGames *really* wanted to, they could ban you for this.
Mostly saying this to cover my ass and I highly doubt they would do something like that.

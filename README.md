# Upgraded Cymbal Monkey for BO2 Zombies (Plutonium)

Black Ops 3's Pack-a-Punched Cymbal Monkey from Gorod Krovi, in Black Ops 2 Zombies. It brings BO3's own bass pulse, dubstep song, voice lines, glow and bigger explosion.

### [⬇ Download the latest version](https://github.com/MaliceDevelops/upgraded-cymbal-monkey-bo2/releases/latest)

Under **Assets**, download `Upgraded_Cymbal_Monkey_v<version>.zip`.

## How it works

- **Pack-a-Punch your monkeys.** At a working Pack-a-Punch, hold your Cymbal Monkeys out (hold the button you throw them with), look at the machine and press Use. It costs 5000 (1000 in a Bonfire Sale). The machine plays its show like it does for a gun, then you take **4 upgraded monkeys**.
- **Bass pulse.** Once an upgraded monkey lands, it pulses every second and hurts every zombie close to it, using BO3's damage numbers.
- **Dubstep.** It plays BO3's dubstep song instead of the normal one, with its own voice lines.
- **Bigger explosion:** BO3's radius and damage for the upgraded monkey.
- **Everything else** works like the normal monkey: zombies go for it, and Samantha takes one thrown out of the map.
- **Maps.** It works on every BO2 zombies map with Cymbal Monkeys and a Pack-a-Punch, and on the **Zombies Declassified** maps if you have it.

## Install

1. Close Black Ops 2.
2. Unzip the download anywhere and double-click **Install.bat**.
3. A window lists all of my mods, each with a tick box, with the Upgraded Cymbal Monkey already ticked. Tick any others you want (like the [Apothicon Servant](https://github.com/MaliceDevelops/apothicon-servant-bo2)). Only the ticked mods are downloaded, each from its own GitHub page, and they all work together in the same game.
4. Choose where they go, press **Install** and play:
   - **Into Zombies Declassified:** launch it like always. The mods work on its maps and on the normal BO2 maps. To play Zombies Declassified without them, press **Turn off** in the installer (**Turn on** puts them back).
   - **As a mod of their own** (the only choice without Zombies Declassified): open **Mods**, pick **MaliceDevelops Mods**, then play any map.

The installer stays on your PC: a **MaliceDevelops BO2 Mods** shortcut on your desktop and in the Start menu opens it again, so you don't need to keep the zip.

Install.bat needs Windows 10 or 11 and an internet connection. To install by hand instead, follow `README.txt` in the download.

Windows may warn about running a downloaded `.bat`. Install.bat only downloads my mods from github.com/MaliceDevelops (checking every file's SHA-256) and copies them; you can read `installer\install.ps1` to check.

## Add, remove or update mods

Open the **MaliceDevelops BO2 Mods** shortcut (or run Install.bat again): tick a mod to add it, untick it (or press its **Uninstall** button) to remove it. It always installs the newest versions, keeps your settings, and doesn't download again what's already up to date. If a mod acts broken, press **Repair**: it downloads again only what's missing or damaged.

## Uninstall

Close BO2 and press **Uninstall all** in the installer (or double-click **Uninstall.bat**). It removes all of my mods, the shortcuts and the installer kept on your PC, and puts back anything it set aside.

## Good to know

- **Co-op:** everyone in the game needs the same mods ticked.
- **Other mods:** script mods like B2OP work fine alongside. Zombies Declassified has two free slots for mods that bring their own fastfile, and all of my mods together use one, so another fastfile mod can use the other.
- **Only what you tick:** a mod you don't tick isn't downloaded or installed. All my mods share one small file (a few MB); each mod's textures, scripts and sounds are separate.
- **After a Zombies Declassified update or install:** if upgrading monkeys stops working, open the installer and press **Repair**.
- **Who's Who and Tombstone** give back normal monkeys, not upgraded ones.

## Bugs

Open an [issue](https://github.com/MaliceDevelops/upgraded-cymbal-monkey-bo2/issues). Include:

- the map,
- whether you have Zombies Declassified,
- the lines starting with `MKY >>` from `%LOCALAPPDATA%\Plutonium\storage\t6\main\console_zm.log`.

## Changes

See [CHANGELOG.md](CHANGELOG.md).

## Credits

Made by **MaliceKy**. Built with [OpenAssetTools](https://github.com/Laupetin/OpenAssetTools) and [Plutonium](https://plutonium.pw).

The upgraded Cymbal Monkey's effects, song, sounds and voice lines are © Activision / Treyarch, from Call of Duty: Black Ops III. This is a free fan mod, not affiliated with or endorsed by Activision. Don't sell it.

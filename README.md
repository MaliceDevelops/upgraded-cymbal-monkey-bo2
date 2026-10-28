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
3. Play. The installer checks for Zombies Declassified by itself:
   - **With Zombies Declassified:** launch it like always. It works on its maps and on the normal BO2 maps.
   - **Without it:** start Zombies, open **Mods**, pick **Upgraded Cymbal Monkey**, then play any map.

### Merge with the Apothicon Servant

Have the [Apothicon Servant](https://github.com/MaliceDevelops/apothicon-servant-bo2) installed too? Install.bat asks what you want:

1. **Merge them** (just press Enter): both work in the same game. With Zombies Declassified, both go into it. Without it, they become one mod in the Mods menu: **Apothicon Servant + Upgraded Cymbal Monkey**.
2. **Keep them apart:** each stays its own mod. Without Zombies Declassified, you pick one or the other in the Mods menu.

The download carries the Apothicon Servant too, so merging also brings it up to that version, and its settings are kept. Uninstalling one of a merged pair leaves the other working.

Install.bat needs Windows 10 or 11. To install by hand instead, follow `README.txt` in the download.

Windows may warn about running a downloaded `.bat`. Install.bat only copies the mod's files; you can read `installer\install.ps1` to check.

## Update

Download the newest version from the link above, close BO2 and run its **Install.bat**. It replaces the old version.

## Uninstall

Close BO2 and double-click **Uninstall.bat**. It removes exactly what Install.bat added and puts back anything it set aside.

## Good to know

- **Co-op:** everyone in the game needs the mod installed.
- **Other mods:** script mods like B2OP work fine alongside it.
- **One fastfile mod in ZD:** Zombies Declassified only has room for **one** mod with its own fastfile (`mods\dlc5\mod_patch.ff`). If you already have one, the installer sets it aside, and Uninstall.bat puts it back. Only one of the two works at a time.
- **The Apothicon Servant** needs that slot too. Merged (see above), both fit.
- **Installed another fastfile mod later:** maps can fail to load. Run this mod's Uninstall.bat, or its Install.bat to switch back to it.
- **After a Zombies Declassified update or install:** if upgrading monkeys stops working, run Install.bat again.
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

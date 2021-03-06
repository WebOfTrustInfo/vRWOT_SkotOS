# "SkotOS" Skotos Open Source Game Library

This is a pre-release version of the Skotos Open Source game library, aka "SkotOS", written for use with [Dworkin's Game Driver](https://github.com/dworkin/dgd), aka "DGD". It a fourth-generation text MUD engine that has been in devopment and active use for almost two decades by [Skotos Tech](http://www.skotos.net/) in a number of commercial web-centric prose online games, including [Castle Marrach](http://www.skotos.net/games/marrach/), [Ironclaw Online](http://www.skotos.net/games/ironclaw/), [Lovecraft Country](http://www.lovecraftcountry.com/comic/), and [The Lazurus Project](http://www.lazarus-project.net/). 

## Status

This version is pre-release and unsupported — installation is difficult, documentation is minimal, and the web client experience needs a lot of work. The main goal of this initial release was to remove proprietary game content and and personal information from the commercial version used in games offered by Skotos Tech.

We are seeking volunteers to take this code to the 1.0 level suitable for anyone to quickly install the game and create their own web-centric prose games.

## Dev Installation

Are you on a Mac? If you run dev_scripts/mac_setup.sh, the script will check out the other repos you need such as DGD itself, the websockets tunnel and the web client. It will even patch DGD for you before building it. All those repos will wind up next to wherever you checked out SkotOS, so make sure that's wher e you want it!

Linux setup isn't much harder, but you'll need to change out Homebrew-based commands for your package manager of choice. Have a look at dev_scripts/mac_setup.sh. You'll probably also have to change things like the install location of NGinX.

## Docs

See [SkotOS-Doc](https://ChatTheatre.github.io/SkotOS-Doc).

## Copyright & Open Source Licenses

The library (SkotOS) and the shared game code and objects in this repository or copyright © 1999-2018 by [Skotos Tech, Inc.](https://www.skotos.net) 

The library itself (all the portions written in LPC) and library documentation are licensed under the [GNU Affero General Public License 3.0](https://www.gnu.org/licenses/agpl-3.0.en.html). All other documentation, the shared game code and common objects (written in a combination of Merry code & XML data) are licensed under the [Creative Commons Attribution Share-Alike 3.0](https://creativecommons.org/licenses/by-sa/3.0/deed.en) license. There is no requirement to release your own game code and objects under any open source license, but any derivative works of the library (AGPL) or contributions to the shared game code and objects (CC-SA) must be released under the same license. All uses of this code must prominently give attribution to "Skotos Tech, Inc" and link to https://www.skotos.net .

## Contributions

We welcome contributions back to this library and to shared game code and objects, but we do require a Contributors License to be signed by any contributor. The contributors license is still a work-in-progress, contact Shannon Appelcline <ShannonA@skotos.net> for more information.

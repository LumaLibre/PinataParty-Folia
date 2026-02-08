### PinataParty on Folia!

This is a patcher for the popular [PinataParty](https://www.spigotmc.org/resources/59318/) plugin,
which adds support for [Folia](https://github.com/PaperMC/Folia).


## Usage

> [!NOTE]
> You need to provide your own copy of the PinataParty plugin jar.

1. Place the PinataParty jar in the `sources/` directory. Your file should be named `PinataParty.jar`.
2. Run `./gradlew setupVineFlower` to download and set up VineFlower.
3. Run `./gradlew decompileAndApplyPatches` to decompile PinataParty and apply the patches.
4. Run `./gradlew build` to get an executable jar in the `build/libs/` directory.
5. Enjoy! Please make an issue on this repository if you encounter any bugs.


## Licenses

This repository contains original patch files authored by me.
These patch files and the tooling to apply these patch files are licensed under the MIT License.
The underlying software is not included and remains the property of its respective copyright holder.
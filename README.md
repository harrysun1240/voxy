# Voxy (unofficial fork: Minecraft 26.3 + Sodium 0.9.3)

Voxy is an LoD rendering mod for minecraft.

This is a personal fork. It is not the official Voxy, and the Voxy developers do not support it.

## Credits

Voxy is made by MCRcortex (Cortex) and the Voxy contributors: https://github.com/MCRcortex/voxy. All rights to Voxy belong to MCRcortex (see LICENSE.md).

The Minecraft 26.3 port this fork is based on was made by TotallyNotTech: https://github.com/TotallyNotTech/voxy

The small changes listed below were made by harrysun1240.

## Changes in this fork

Removed 5 outdated OpenGL entries from `src/main/resources/voxy.accesswidener`. These classes moved in 26.3, so the build failed on them.

Changed `gradle.properties` to build against Sodium `mc26.3-0.9.3-alpha.1`. Sodium 0.9.2 is still allowed.

These fixes were also sent back to the TotallyNotTech fork as a pull request.

## License

Voxy's license is "All rights reserved. Do not redistribute." (see LICENSE.md). This fork only exists so the changes can be reviewed and sent back to the original project. No builds are published here, so please don't upload jars made from this repo anywhere.

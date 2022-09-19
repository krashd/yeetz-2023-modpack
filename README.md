# yeetz-2023-modpack

This modpack is built using packwiz for seamless updates. Any existing instances will need adjusting to use the packwiz bootloader for Minecraft.

Further information regarding packwiz can be found https://packwiz.infra.link/

## Manual Installation on existing instance
1. Head to https://github.com/packwiz/packwiz-installer and download the latest release. Place the jar into your minecraft or .minecraft folder (this folder also contains options.txt)
2. Head to your instance setting, (Edit Instance -> Settings -> Custom commands, enable Custom Commands and paste the following command into the pre-launch command field.
```"$INST_JAVA" -jar packwiz-installer-bootstrap.jar https://krashd.github.io/yeetz-2023-modpack/pack.toml```
3. Remove all of your mods and resource packs for this instance.

## MultiMC/PolyMC modpack install (new instance)
1. download the latest from releases.
2. import modpack using MultiMC/PolyMC.
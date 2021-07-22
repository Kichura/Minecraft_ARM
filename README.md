# Minecraft (ARM Support)
An experimental MultiMC instance for trying to add ARM support to Minecraft such as M1 devices. No mods will be included except latest snapshot available.

(This project is not meant for full reproduction as it can contain bugs/glitches, If you are sensitive to these kinds of issues; Please use pure vanilla of minecraft instead)

### Requirements
A [newer java version](https://jdk.java.net/17) is required for ARM devices,
LWJGL [3.2.3](https://pastebin.com/raw/DabMxEjh) or [3.3.0-Snapshot](https://pastebin.com/raw/c9EfPWSk) is required for ARM devices and 
Minecraft 1.16.5 or newer is required for both to work as 1.8.9 does not make use of them + LWJGL 3.2.3 only has Linux-ARM64 support.

### Installing the modpack
Download the modpack by pressing "code" and then Download ZIP. From there you need to import the ZIP using MultiMC by clicking on "Add instance" -> Import from ZIP.
Once installed, Edit the instance and then jump to "settings" and replace the original javaw/java executable with the updated one. To update LWJGL (if it isn't yet); Go to "Version" and customize LWJGL 3 then edit it so that you can one of the LWJGL versions as above.

### Disclaimer
While this modpack claims to do what it says on the tin, it is very experimental and can lead to problems unless you know what you are doing then feel free to test it out for yourself; otherwise don't do this at all.

### License
Minecraft_ARM is license under MIT, a free and open-source license. For more information, please see the [license file](https://github.com/Kichura/minecraft_arm/blob/standard/LICENSE).

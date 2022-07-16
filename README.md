# HSLIW-BOOTKIT
#### HDD SSD Loneicewolf Bootkit

## :radioactive: WARNING :radioactive:
## Please before continuing; read both the `DISCLAIMER.MD` and `WARNINGS.MD` files.


this is a Bootkit at firmware level I made for some specific brands of SSD and HDD disks;
And (`by the time writing this`) I am still hesitating to make this repository (why? because it will contain reversed closed-source code, but also - most importantly; a out-of-the-box working bootkit that you can just "apply" (if you wanted to.. which is a **bad idea**) to a SSD/HDD's firmware.
But I chose It's better if I upload(thereby making signatures known to AV's) this ; and redacting anything that shouldn't be public. Like for example; code that is not open source (like the firmware) 
so; you will yourself have to dump firmware and then; load this bootkit.




# Methods of loading the bootkit onto the Disks Firmware
there are 3 ways;
- 1 `easiest and most 'non' risky method` if a disk already is loaded with the bootkit(that is you have loaded it in advance) then you can use a executable I will provide in the next few months.
- 2 `JTAG` (you should know what this is)
- 3 `hardest and most destructive(hazardous) method (for not only the disk, for the health as well(heat/poisonous hazards))` Wires soldered in place, on to the controller card, thereby making a hardware `bridge`, which will be used to `intercept`(aka tap) the data-flow between the `**Disk**`  `**Disks Controller**` `**The Computer system that is connected to the Disk**`



# Supported Vendors
#### I have only so far succeeded in:
- Some Seagate HDD's
- Most Samsung SSD's


# Supported OS's (Operating Systems)

#### Currently only has support for windows. (that is; For  loading and unloading the bootkit.)

Once loaded, doesn't matter what os it is; it resides in the Firmware of the disk itself. so it will just do as instructed; either in advance(pre configured) or wait for further instructions(trigger words) (`example of a trigger word: echo "SOMETHING THAT SHOULD NOT WORK" >/dev/SOME/PATH/THAT/ABSOLUTELY/DOESNT/EXIST`



## Photos

- will upload photo of each Method mentioned (above), and it's Sub-Stages(preparing,loading,testing,unloading,verifying)


## POC's (Proof Of Concepts)


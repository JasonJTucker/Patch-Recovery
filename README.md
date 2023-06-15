# Patch-Recovery
This script patches recovery images of Samsung to enable Fastbootd. Based on Phh's [script](https://github.com/phhusson/samsung-galaxy-a51-gsi-boot) and Johx22's [CI service](https://github.com/Johx22/Patch-Recovery)

# How to use:
- Clone this repo
- chmod a+x magiskboot
- Copy recovery.img or recovery.img.lz4 from your original ROM to the repo folder
- Run patch.sh
- You should end up with Odin-flashable fastbootd-recovery.tar in the repo folder

# Credits
- [Phhusson](https://github.com/phhusson) Without his script nothing would be possible at the first place
- [James Nguyen](https://github.com/thongass000) Helping me in simplifying the scripts and tweaking it
- [Johx22](https://github.com/Johx22) for the CI service repo this was forked from

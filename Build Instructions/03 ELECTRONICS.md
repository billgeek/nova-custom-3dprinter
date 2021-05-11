# Electronics

I'm not going to go into detail on how to install electronics for a 3D printer as there are so many detailed articles and videos in the subject. Instead, here's a quick to-do list of what I had to do:

- [ ] Install the hotend assembly of your choice. I went for an assembled Ender 3 hotend (future upgrade opportunity here!) and the Hero Me Gen 5 system found here: https://www.thingiverse.com/thing:4460970
- [ ] Optionally install your ABL, inductive probe, proximity sensor or BLTouch of choice.
- [ ] Print and install an electronics enclosure of your choice. There are plenty to choose from on Thingiverse, but I decided to use this one: https://www.thingiverse.com/thing:4338524
- [ ] Install your Mainboard and Mosfets into the enclosure
- [ ] Wire up all four motors (X, Y and dual Z) to the mainboard.
- [ ] Print and install an LCD cover of your choice. There are plenty to choose from on Thingiverse, but I decided to use this one: https://www.thingiverse.com/thing:4547059
- [ ] Install your LCD and connect it to the mainboard.
- [ ] Wire your Power Supply to the mainboard and MOSFET boards.
- [ ] Connect your hotend and heated bed to the MOSFETs.

If all went well, you should now have a semi-operational 3D printer!

The final step in the process would be to download, configure and flash the Firmware of your choice. I'm using Marlin and have included the configuration files I used in this repository.

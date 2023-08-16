# Neo Geo MVS Pause Button Mod v1.1
A simple mod to add pause button functionality to a Neo Geo MVS board.

Created by Derf of [ConsoleMods.org](https://www.consolemods.org/wiki/Main_Page).

Massive thanks to [12voltman](https://github.com/12voltman?tab=repositories) as it wouldn't have been possible without his help!

<img src="https://www.consolemods.org/wiki/images/f/f9/MVS_Pause_Button.jpg" width="49%" height="auto"> <img src="https://www.consolemods.org/wiki/images/b/bc/MVS_Pause_Button_2.jpg" width="49%" height="auto">

# Concept and Demo

The Neo Geo MVS does not normally support pausing of games through regular controls. However, (all?) games support a special pause mode when DIP switch #8 is flipped to the ON position during gameplay. This is a graceful pause, as background animations and sound generally continue playing. This mod simply allows you to use a dedicated button on your controller or control panel to electrically toggle this DIP switch. In short, this is a momentary-to-toggle switch board.

Note that this has only been test fit to sit flush on a MV-1AX motherboard. If you install this mod on a different motherboard, please let us know if it sits flush and we can note that here.

Click the image below to see a demo of the mod in action.

[![Neo Geo MVS Pause Button Mod](http://img.youtube.com/vi/1Y2-J27g2OU/0.jpg)](https://www.youtube.com/watch?v=1Y2-J27g2OU "Neo Geo MVS Pause Button Mod Demo")

# Manufacturing

* Feel free to remove all silkscreen except "ConsoleMods.org".
* 1.0mm thickness recommended.

# Parts

([Shopping cart containing the items below](https://www.digikey.com/en/mylists/list/QAYD25AZV5))

* One AIP74LVC2G14GC363 or equivalent SOT-363 dual inverter Schmitt trigger (INV).
* One SN74LVC1G175DCKR or equivalent SOT-363 flip flop (FLP).
* One MCP130T-315I/TT or equivalent SOT-23-3 chip for Power on Reset (POR).
* One 1kΩ resistor, preferably 0603 size (R1).
* One 10kΩ resistor, preferably 0603 size (R2).
* One 150Ω resistor, preferably 0603 size (R3).
* Two 100nF (0.1µF) capacitors, preferably 0603 size (C1 and C2).

# Installation

1. Assemble pause button PCB. Positions are marked on the board as described in the parts list.
2. Place PCB onto motherboard and align with DIP switch #8 and solder into place. <br> <img src="https://www.consolemods.org/wiki/images/c/cc/MVS_Pause_Button_Install_1.jpg" width="auto" height="300px">
3. Solder a wire from a 5V source (such as the "C" pad marked in the picture below) to the 5V pad on the PCB.
4. Solder a wire from your desired button to act as the pause button to the SEL pad on the PCB. The suggested button is the Player 1 Select button marked in the image below. Multiple buttons can be wired to the SEL pad at once. <br> <img src="https://www.consolemods.org/wiki/images/8/80/MVS_Pause_Button_Install_2.jpg" width="100%" height="auto">
5. Press the pause button during gameplay to pause the game!

# Schematic

<img src="https://www.consolemods.org/wiki/images/0/03/MVS_Pause_Button_Schematic.jpg" width="99%" height="auto">

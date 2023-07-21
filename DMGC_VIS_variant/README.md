This is a modified version of the MouseBitLab DMGC project. Major changes are the following:
- Lipo power board
- Audio board with all the audio circuits on it in which 1w speaker or the original speaker is directly connected (Audio is not sent to the IPS front PCB and, for this reason, any power absorbion on the front PCB does not affect audio)
- DMG donor is not required (only the link port is needed and it can be sourced directly from the 4-player adapter DMG-07 which is cheap and can source 3 link ports)
- Since the power DC is a new 2.5A jack the problems related to it in the original DMGC are solved in this version  (DC Jack is a 2.5x0.7mm Jack and you can use a USB-C adapter with a standard USB-C 5v charger. Do not exceed 6v otherwise the charger will be broken).
## Disclaimer

**Before I go any further, please read this VERY important disclaimer, if you are thinking about making this yourself.**

If you choose to build this project yourself, be warned - this is a considerably advanced, and expensive build. You must be comfortable with the fact that you may lose or damage expensive components. **You are 100% liable for any damage done to your property or yourself. I am not responsible for any damage or loss of property incurred while attempting this project, or after completion of the project - you alone accept all risk.** While I am confident in this design, I cannot claim full compatibility with every system configuration. And there may be latent issues that have yet to crop up. I will update this repo if I encounter any, and if you see anything I may have missed, or some dubious design choice, feel free to ask questions or comment as such. Corrections are welcome. However, I **will not** obligate myself to providing tech support. You accept all risks and costs associated to this build if you choose to attempt it.

![image](https://user-images.githubusercontent.com/97127539/209872784-c513c013-3432-4aa2-80cf-81ea6a5e8c54.png)

**DO NOT attempt this project if you are uncomfortable or inexperienced with detailed electronics troubleshooting, or are not proficient in soldering! You will AT MINIMUM need to be proficient in drag soldering and hot air reflowing. If you have not gained proficiency in these soldering skills, DO NOT ATTEMPT THIS PROJECT.**

(If you attempt the build, start with attempting to assemble DMGC-PWR-01. This is the toughest board to assemble, and it requires no donor components.)

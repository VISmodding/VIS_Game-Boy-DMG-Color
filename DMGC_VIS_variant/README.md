## This readme file is not it is not completed yet, but PCBs and BOM files are good to be used...

This is a modified version of the [MouseBitLab](https://github.com/MouseBiteLabs/Game-Boy-DMG-Color) DMGC project. The changes I have made are the following:
- Lipo power board
- Audio board with all the audio circuits on it in which 1w speaker or the original speaker is directly connected (Audio is not sent to the IPS front PCB and, for this reason, any power absorbing on the front PCB affect a little bit the audio)
- DMG donor is not required (only the link port is needed, and it can be sourced directly from the 4-player adapter DMG-07 which is cheap and can source 3 link ports)
- Since the power DC is a new 2.5A jack, the problems related to it in the original DMGC are solved in this version  (DC Jack is a 2.5x0.7mm Jack, and you can use a USB-C adapter with a standard USB-C 5v charger. Do not exceed 6v otherwise the charger will be broken).

## UPDATED BOARD FILE!!!

The 5v line sent to the IPS board is now a totally different line than the filtered 5v line used by the mainboard and audio board. This separation allows to elimination of all the noise added on the 5v line by IPS LCD and RGB LEDs. This means cleaner audio whose noise is amplified with 1 Watt speaker and very high volume. The new file is named *Gerber_DMGC_VIS_variant_low_noise_1_mm* and, in the case you have already produced the old file named *Gerber_DMGC_VIS_variant_1_mm* send me an email and I will explain how you can act to add the new feature on the old version.

## Warning: 

<ins>I have updated Gerber file of the mainboard to v2.31, in which an important fix has been done. If you have produced v2.3 of the mainboard, send me an email and I will tell you the fix that must be done.</ins>

## At the end of the production or easyEda files, there is the thickness of the PCBs to be used for production to have a good fit in the shell!!!

## Disclaimer

**Before I go any further, please read this VERY important disclaimer if you are thinking about making this yourself.**

If you choose to build this project yourself, be warned - this is a considerably advanced and expensive build. You must be comfortable with the fact that you may lose or damage expensive components. **You are 100% liable for any damage done to your property or yourself. I am not responsible for any damage or loss of property incurred while attempting this project, or after completion of the project - you alone accept all risk.** While I am confident in this design, I cannot claim full compatibility with every system configuration. And there may be latent issues that have yet to crop up. I will update this repo if I encounter any, and if you see anything I may have missed, or some dubious design choice, feel free to ask questions or comment as such. Corrections are welcome. However, I **will not** obligate myself to providing tech support. You accept all risks and costs associated with this build if you choose to attempt it.

![image](https://user-images.githubusercontent.com/97127539/209872784-c513c013-3432-4aa2-80cf-81ea6a5e8c54.png)

**DO NOT attempt this project if you are uncomfortable or inexperienced with detailed electronics troubleshooting or are not proficient in soldering! You will, AT MINIMUM, need to be proficient in drag soldering and hot air reflowing. If you have not gained proficiency in these soldering skills, DO NOT ATTEMPT THIS PROJECT.**

## Support VIS projects

I have several stuffs in mind, and I will also share my normal Gameboy DMG work [YouTube Channel](https://www.youtube.com/channel/UC17bQxOnCBejYQG4rzEg3jA), but since developing these things has a high cost in materials and prototypes, a little [PayPal](https://www.paypal.com/donate/?hosted_button_id=RJM3TVFW38ZXL) donation is appreciated.

## Contacts

**email**: vis.modding@gmail.com <br />

**discord**: you can find me as vis_modding on several servers (BennVenn, Mouse Bit Lab, Retrosix modding, Game Boy)







# OPN-OPLL-MegaMod-v0.4
 The optimized OPN+OPLL music module removes many useless diodes, combines the design of RE2-YM2413, and uses copper to isolate the digital and analog grounds, which greatly reduces noise.  
 This hardware is verified and can be used with confidence. Note that only the original TL074C can be used, any other replacement models will cause continuous power supply noise, I tested LF347 and TL084 and both got noise.  
 To get a louder volume, please change R11, R14 to 10k; R3, R7 to 20k. I will restore the overall volume adjustment function in the next version.  
 The new version of the OPLL+OPN module can be said to integrate all my research results, including ground isolation, audio subtraction mixer, YM2413 clone switch, UM3567 compatible socket, YM2413-F pad. The circuit of the OPN part has also been greatly modified to obtain a higher volume.  
 This is probably the best sounding OPLL circuit ever, almost as pure as the vgmplay emulation, never before seen perfect sound, as clean as OPL2. Any similar projects can't compare, 1ChipMSX, FMPAC, etc.  
For the stereo SSG circuit, I modified the resistors on both sides to balance the volume.    
And I feel that after the audio circuit is changed to full SMD, the soldering efficiency is much improved. However, I have bought many fake quad op amps, and those have very poor sound quality, such as fake TL084 and LF347. Perhaps only the original TL074C can work correctly at 5V.  

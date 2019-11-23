# PHBankGBC - Pokémon Bank for Gen I and II 3DS games
This is a fork of [JoycieC's PHBankGB](https://github.com/JoycieC/PHBankGB/tree/GEN2), which is a fork of [gocario's PHBankGB](https://github.com/gocario/PHBankGB).

The goal of this repo is to implement GEN II functionality to PHBankGB, because it's been around 2 years since G/S/C were released on 3DS and nothing of this sort has been made yet.

# Project updates
* **11/23/2019:** I've tried to build the .cia, but devkitPro no longer supports [sfillib](https://github.com/xerpi/sfillib) nor [sf2dlib](https://github.com/xerpi/sf2dlib), since the latter is deprecated. I've tried building those libraries myself, but it seems that doesn't really work and I'm not experienced enough to know how to properly fix it yet. The best long-term solution would be to remove those dependencies and use [citro3D](https://github.com/fincs/citro3d) directly, and that's going to take a lot more time than I had initially expected. (Not that I'm in a rush to finish this, though.)
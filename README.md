# MiSTer_update_games.sh for use with MiSTerCade JAMMA adapter

Download public ROM contents from archive.org into /media/fat/games for educational purposes 

### 
Start with fresh SD
https://github.com/michaelshmitty/SD-Installer-macos_MiSTer

###
Run update all after boot
https://github.com/theypsilon/Update_All_MiSTer

###
Move configs over
https://github.com/misteraddons/MiSTercade

# raw wget commands
wget https://github.com/develar/7zip-bin/raw/master/linux/arm/7za

wget https://archive.org/download/Atari2600FullRomCollectionReuploadByDataghost/Atari%202600.7z
./7za x Atari 2600.7z

wget https://archive.org/download/Atari5200Collection/Atari-5200.7z
./7za x Atari-5200.7z

wget https://archive.org/download/Atari800FullRomCollectionReuploadByDataghost/Atari800.rar
unrar Atari800.rar

wget https://archive.org/compress/AtariSTRomCollectionByGhostware

wget https://archive.org/compress/C64RomCollectionByGhostware

wget "https://archive.org/download/ColecoVisionCollection/ColecoVision.7z"
./7za ColecoVision.7z

wget https://archive.org/download/Cyles_Gameboy_roms/GB.zip

wget "https://archive.org/compress/GameBoyAdvanceTOSEC/formats=ZIP&file=/GameBoyAdvanceTOSEC.zip"

wget https://archive.org/download/SegaGenesisCollection/Sega-Genesis.7z
./7za x Sega-Genesis.7z

wget "https://archive.org/compress/MSXRomCollectionByGhostware/formats=ZIP&file=/MSXRomCollectionByGhostware.zip"
unzip MSXRomCollectionByGhostware.zip

wget "https://archive.org/compress/MSX2RomCollectionByGhostware/formats=ZIP&file=/MSX2RomCollectionByGhostware.zip"
unzip MSX2RomCollectionByGhostware.zip

wget "https://archive.org/compress/neo-geo-mvs-romset/formats=ZIP&file=/neo-geo-mvs-romset.zip"
unzip neo-geo-mvs-romset.zip

wget "https://archive.org/compress/neo-geo-aes-romset/formats=ZIP&file=/neo-geo-aes-romset.zip"
unzip neo-geo-aes-romset.zip

wget "https://archive.org/compress/SegaMasterSystemCollectionByGhostware/formats=ZIP&file=/SegaMasterSystemCollectionByGhostware.zip"

wget https://ia802905.us.archive.org/35/items/SNESSpecialCollection/Super_Nintendo_Entertainment_System.7z
./7za x Super_Nintendo_Entertainment_System.7z

wget https://archive.org/download/TurboGrafx16AndPCEngineChampionCollection/Champion%20Collection%20-%20TurboGrafx-16%20and%20PC%20Engine.7z
./7za x Champion\ Collection\ -\ TurboGrafx-16\ and\ PC\ Engine.7z 








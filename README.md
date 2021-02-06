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
cd /media/fat/downloads/
wget https://github.com/develar/7zip-bin/raw/master/linux/arm/7za
chmod +x 7za

cd /media/fat/downloads/
wget https://archive.org/download/Atari2600FullRomCollectionReuploadByDataghost/Atari%202600.7z
./7za x Atari 2600.7z

cd /media/fat/downloads/
wget https://archive.org/download/Atari5200Collection/Atari-5200.7z
./7za x Atari-5200.7z

cd /media/fat/downloads/
wget https://archive.org/download/Atari800FullRomCollectionReuploadByDataghost/Atari800.rar
unrar Atari800.rar

cd /media/fat/downloads/
wget https://archive.org/compress/AtariSTRomCollectionByGhostware
unzip AtariSTRomCollectionByGhostware

cd /media/fat/downloads/
wget https://archive.org/compress/C64RomCollectionByGhostware
unzip C64RomCollectionByGhostware

cd /media/fat/downloads/
wget "https://archive.org/download/ColecoVisionCollection/ColecoVision.7z"
./7za ColecoVision.7z

cd /media/fat/downloads/
wget https://archive.org/download/Cyles_Gameboy_roms/GB.zip
unzip GB.zip

cd /media/fat/downloads/
wget https://archive.org/download/SegaGenesisCollection/Sega-Genesis.7z
./7za x Sega-Genesis.7z

cd /media/fat/downloads/
wget "https://archive.org/compress/MSXRomCollectionByGhostware/formats=ZIP&file=/MSXRomCollectionByGhostware.zip"
unzip MSXRomCollectionByGhostware.zip

cd /media/fat/downloads/
wget "https://archive.org/compress/MSX2RomCollectionByGhostware/formats=ZIP&file=/MSX2RomCollectionByGhostware.zip"
unzip MSX2RomCollectionByGhostware.zip

cd /media/fat/downloads/
wget "https://archive.org/compress/neo-geo-mvs-romset/formats=ZIP&file=/neo-geo-mvs-romset.zip"
unzip neo-geo-mvs-romset.zip

cd /media/fat/downloads/
wget "https://archive.org/compress/neo-geo-aes-romset/formats=ZIP&file=/neo-geo-aes-romset.zip"
unzip neo-geo-aes-romset.zip

cd /media/fat/downloads/
wget https://archive.org/download/famicom-disk-system-champion-collection/Champion%20Collection%20-%20Famicom%20Disk%20System.zip
unzip Champion Collection - Famicom Disk System.zip

cd /media/fat/downloads/
wget https://archive.org/download/NESrompack/NESroms.rar
cd /media/fat/games/NES
unrar-nonfree e /media/fat/downloads/NESroms.rar

cd /media/fat/downloads/
wget "https://archive.org/compress/SegaMasterSystemCollectionByGhostware/formats=ZIP&file=/SegaMasterSystemCollectionByGhostware.zip"
unzip SegaMasterSystemCollectionByGhostware.zip

cd /media/fat/downloads/
wget https://archive.org/compress/SNESSpecialCollection
./7za x Super_Nintendo_Entertainment_System.7z

cd /media/fat/downloads/
wget https://archive.org/download/TurboGrafx16AndPCEngineChampionCollection/Champion%20Collection%20-%20TurboGrafx-16%20and%20PC%20Engine.7z
./7za x Champion\ Collection\ -\ TurboGrafx-16\ and\ PC\ Engine.7z 

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
cd /media/fat/games/ATARI2600
./7za x /media/fat/downloads/Atari 2600.7z

cd /media/fat/downloads/
wget https://archive.org/download/Atari5200Collection/Atari-5200.7z
cd /media/fat/games/ATARI5200
./7za x /media/fat/downloads/Atari-5200.7z

cd /media/fat/downloads/
wget https://archive.org/download/Atari800FullRomCollectionReuploadByDataghost/Atari800.rar
cd /media/fat/games/ATARI800
unrar /media/fat/downloads/Atari800.rar

cd /media/fat/downloads/
wget https://archive.org/compress/C64RomCollectionByGhostware
cd /media/fat/games/C64
unzip /media/fat/downloads/C64RomCollectionByGhostware

cd /media/fat/downloads/
wget "https://archive.org/download/ColecoVisionCollection/ColecoVision.7z"
cd /media/fat/games/Coleco
./7za /media/fat/downloads/ColecoVision.7z

cd /media/fat/downloads/
wget https://archive.org/download/Cyles_Gameboy_roms/GB.zip
cd /media/fat/games/GameBoy
unzip /media/fat/downloads/GB.zip

cd /media/fat/downloads/
wget https://archive.org/download/SegaGenesisCollection/Sega-Genesis.7z
cd /media/fat/games/Genesis
./7za x /media/fat/downloads/Sega-Genesis.7z

cd /media/fat/downloads/
wget "https://archive.org/compress/MSXRomCollectionByGhostware/formats=ZIP&file=/MSXRomCollectionByGhostware.zip"
cd /media/fat/games/MSX
unzip /media/fat/downloads/MSXRomCollectionByGhostware.zip

cd /media/fat/downloads/
wget "https://archive.org/compress/MSX2RomCollectionByGhostware/formats=ZIP&file=/MSX2RomCollectionByGhostware.zip"
cd /media/fat/games/MSX
unzip /media/fat/downloads/MSX2RomCollectionByGhostware.zip

cd /media/fat/downloads/
wget "https://archive.org/compress/neo-geo-mvs-romset/formats=ZIP&file=/neo-geo-mvs-romset.zip"
cd /media/fat/games/NeoGeo
unzip /media/fat/downloads/neo-geo-mvs-romset.zip

cd /media/fat/downloads/
wget "https://archive.org/compress/neo-geo-aes-romset/formats=ZIP&file=/neo-geo-aes-romset.zip"
cd /media/fat/games/NeoGeo
unzip /media/fat/downloads/neo-geo-aes-romset.zip

cd /media/fat/downloads/
wget https://archive.org/download/famicom-disk-system-champion-collection/Champion%20Collection%20-%20Famicom%20Disk%20System.zip
mkdir /media/fat/games/NES/Famicom
cd /media/fat/games/NES/Famicom
unzip /media/fat/downloads/Champion Collection - Famicom Disk System.zip
unzip '*.zip'

cd /media/fat/downloads/
wget https://archive.org/download/NESrompack/NESroms.rar
cd /media/fat/games/NES
unrar-nonfree e /media/fat/downloads/NESroms.rar

cd /media/fat/downloads/
wget "https://archive.org/compress/SegaMasterSystemCollectionByGhostware/formats=ZIP&file=/SegaMasterSystemCollectionByGhostware.zip"
cd /media/fat/games/SMS
unzip /media/fat/downloads/SegaMasterSystemCollectionByGhostware.zip

cd /media/fat/downloads/
wget https://archive.org/compress/SNESSpecialCollection
cd /media/fat/games/SNES
./7za x /media/fat/downloads/Super_Nintendo_Entertainment_System.7z

cd /media/fat/downloads/
wget https://archive.org/download/TurboGrafx16AndPCEngineChampionCollection/Champion%20Collection%20-%20TurboGrafx-16%20and%20PC%20Engine.7z
cd /media/fat/games/TGFX16
./7za x /media/fat/downloads/Champion\ Collection\ -\ TurboGrafx-16\ and\ PC\ Engine.7z 

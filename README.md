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
```
cd /media/fat/downloads/
wget https://github.com/develar/7zip-bin/raw/master/linux/arm/7za
chmod +x 7za

cd /media/fat/downloads/
wget https://archive.org/download/Atari2600FullRomCollectionReuploadByDataghost/Atari%202600.7z
cd /media/fat/games/ATARI2600
/media/fat/downloads/7za x /media/fat/downloads/Atari\ 2600.7z
mv Atari\ 2600/* . 
rm -rf Atari\ 2600/

cd /media/fat/downloads/
wget https://archive.org/download/Atari5200Collection/Atari-5200.7z
cd /media/fat/games/ATARI5200
/media/fat/downloads/7za x /media/fat/downloads/Atari-5200.7z

cd /media/fat/downloads/
wget https://archive.org/download/Atari800FullRomCollectionReuploadByDataghost/Atari800.rar
cd /media/fat/games/ATARI800
unrar-nonfree x /media/fat/downloads/Atari800.rar
cd Atari800/
unzip '*.zip'
rm *.zip
cd /media/fat/games/ATARI800
mv Atari800/* .
rm -rf Atari800

cd /media/fat/downloads/
wget https://archive.org/compress/C64RomCollectionByGhostware
cd /media/fat/games/C64
unzip /media/fat/downloads/C64RomCollectionByGhostware 

cd /media/fat/downloads/
wget "https://archive.org/download/ColecoVisionCollection/ColecoVision.7z"
cd /media/fat/games/Coleco
/media/fat/downloads/7za x /media/fat/downloads/ColecoVision.7z

cd /media/fat/downloads/
wget https://archive.org/download/Cyles_Gameboy_roms/GB.zip
cd /media/fat/games/GameBoy
unzip /media/fat/downloads/GB.zip
cd /media/fat/games/GameBoy/Europe/
unzip '*.zip'
rm *.zip
cd ..
cd /media/fat/games/GameBoy/Hacks/
unzip '*.zip'
rm *.zip
cd ..
cd /media/fat/games/GameBoy/Homebrew
unzip '*.zip'
rm *.zip
cd ..
cd /media/fat/games/GameBoy/Japan
unzip '*.zip'
rm *.zip
cd ..
cd /media/fat/games/GameBoy/Proto-unl-demo-beta-sample
unzip '*.zip'
rm *.zip
cd ..
cd /media/fat/games/GameBoy/Rev
unzip '*.zip'
rm *.zip
cd ..
cd /media/fat/games/GameBoy/Translations
unzip '*.zip'
rm *.zip
cd ..
cd /media/fat/games/GameBoy/USA
unzip '*.zip'
rm *.zip
cd ..

cd /media/fat/downloads/
wget https://archive.org/download/SegaGenesisCollection/Sega-Genesis.7z
cd /media/fat/games/Genesis
/media/fat/downloads/7za x /media/fat/downloads/Sega-Genesis.7z

cd /media/fat/downloads/
wget "https://archive.org/compress/MSXRomCollectionByGhostware/formats=ZIP&file=/MSXRomCollectionByGhostware.zip"
cd /media/fat/games/MSX
unzip /media/fat/downloads/MSXRomCollectionByGhostware.zip
unzip '*.zip'
rm *.zip

cd /media/fat/downloads/
wget "https://archive.org/compress/MSX2RomCollectionByGhostware/formats=ZIP&file=/MSX2RomCollectionByGhostware.zip"
cd /media/fat/games/MSX
unzip /media/fat/downloads/MSX2RomCollectionByGhostware.zip
unzip '*.zip'
rm *.zip

cd /media/fat/downloads/
wget https://archive.org/download/darksoft/Darksoft%20Neo%20Geo%202020-05-12.7z
cd /media/fat/games/NeoGeo/
/media/fat/downloads/7za x Darksoft\ Neo\ Geo\ 2020-05-12.7z
wget https://gitlab.com/loic.petit/darksoft-to-neosd/-/archive/master/darksoft-to-neosd-master.zip
unzip darksoft-to-neosd-master.zip 
#python darksoft-to-neosd-master/convert.py -x 
wget https://github.com/MiSTer-devel/NeoGeo_MiSTer/raw/master/releases/romsets.xml

cd /media/fat/downloads/
wget https://archive.org/download/famicom-disk-system-champion-collection/Champion%20Collection%20-%20Famicom%20Disk%20System.zip
mkdir /media/fat/games/NES/Famicom
cd /media/fat/games/NES/Famicom
unzip /media/fat/downloads/Champion\ Collection\ -\ Famicom\ Disk\ System.zip

cd /media/fat/downloads/
wget https://archive.org/download/NESrompack/NESroms.rar
cd /media/fat/games/NES
unrar-nonfree e /media/fat/downloads/NESroms.rar

cd /media/fat/downloads/
wget "https://archive.org/compress/SegaMasterSystemCollectionByGhostware/formats=ZIP&file=/SegaMasterSystemCollectionByGhostware.zip"
cd /media/fat/games/SMS
unzip /media/fat/downloads/SegaMasterSystemCollectionByGhostware.zip
unzip '*.zip'
rm *.zip

cd /media/fat/downloads/
wget https://archive.org/compress/SNESSpecialCollection
cd /media/fat/games/SNES
/media/fat/downloads/7za x /media/fat/downloads/Super_Nintendo_Entertainment_System.7z

cd /media/fat/downloads/
wget https://archive.org/download/TurboGrafx16AndPCEngineChampionCollection/Champion%20Collection%20-%20TurboGrafx-16%20and%20PC%20Engine.7z
cd /media/fat/games/TGFX16
/media/fat/downloads/7za x /media/fat/downloads/Champion\ Collection\ -\ TurboGrafx-16\ and\ PC\ Engine.7z 
unzip '*.zip'
rm *.zip
```

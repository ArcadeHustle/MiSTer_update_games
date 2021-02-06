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

###
wget https://github.com/develar/7zip-bin/raw/master/linux/arm/7za

wget https://archive.org/download/TurboGrafx16AndPCEngineChampionCollection/Champion%20Collection%20-%20TurboGrafx-16%20and%20PC%20Engine.7z
./7za x Champion\ Collection\ -\ TurboGrafx-16\ and\ PC\ Engine.7z 

wget https://ia802905.us.archive.org/35/items/SNESSpecialCollection/Super_Nintendo_Entertainment_System.7z
./7za x Super_Nintendo_Entertainment_System.7z

wget "https://archive.org/compress/neo-geo-mvs-romset/formats=ZIP&file=/neo-geo-mvs-romset.zip"
unzip neo-geo-mvs-romset.zip

wget "https://archive.org/compress/neo-geo-aes-romset/formats=ZIP&file=/neo-geo-aes-romset.zip"
unzip neo-geo-aes-romset.zip

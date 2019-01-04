# Installation

## Rename repository
* `mv heidisql-ubuntu HeidiSQL`

## Install Wine
* `apt-get install wine`

## Install HeidiSQL in Wine
* `cp HeidiSQL_9.5.0.5196_Setup.exe '~/.wine/drive_c/Program Files/'`
* `wine '~/.wine/drive_c/Program Files/HeidiSQL_9.5.0.5196_Setup.exe'`
* `rm '~/.wine/drive_c/Program Files/HeidiSQL_9.5.0.5196_Setup.exe'`

## Update the files to make them executable
* `cd ~/HeidiSQL`
* `chmod u+x HeidiSQL.desktop`
* `chmod u+x heidisql.sh`

### install scoop 

powershell 3 +

set-executionpolicy remotesigned -scope currentuser

iex (new-object net.webclient).downloadstring('https://get.scoop.sh')

### install main app

scoop install git openssh

### add bucket

scoop bucket extras

scoop bucket add dorado https://github.com/h404bi/dorado

### Check update

scoop update 
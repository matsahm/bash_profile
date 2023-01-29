# bash_profile

## Download mit curl (empfohlen)
```
curl -o ~/.bash_profile_ms https://raw.githubusercontent.com/matsahm/bash_profile/master/.bash_profile_ms
```  

## Download mit wget
```
wget -O ~/.bash_profile_ms https://raw.githubusercontent.com/matsahm/bash_profile/master/.bash_profile_ms
```  

## Download mit git
```
git clone https://github.com/matsahm/bash_profile.git
ln -s $PWD/bash_profile/.bash_profile_ms ~/.bash_profile_ms
```

## Installation
```
echo '. ~/.bash_profile_ms' >> ~/.bash_profile
```

## Anpassung Synology (nur bei erster Installation notwendig)
```
echo '. ~/.bash_profile' >> ~/.bashrc
```  

## Update (benötigt curl)
```
ms_update
```  

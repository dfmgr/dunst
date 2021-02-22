## dunst  
  
dunst notification service
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/dunst/raw/master/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install dunst
```  

Fedora Based:

```shell
yum install dunst
```  

Arch Based:

```shell
pacman -S dunst
```  

MacOS:  

```shell
brew install dunst
```
  
```shell
mv -fv "$HOME/.config/dunst" "$HOME/.config/dunst.bak"
git clone https://github.com/dfmgr/dunst "$HOME/.config/dunst"
```
  
<p align=center>
   <a href="https://travis-ci.com/github/dfmgr/dunst" target="_blank" rel="noopener noreferrer">
     <img src="https://travis-ci.com/dfmgr/dunst.svg?branch=master" alt="Build Status"></a><br />
  <a href="https://wiki.archlinux.org/index.php/dunst" target="_blank" rel="noopener noreferrer">dunst wiki</a>  |  
  <a href="dunst" target="_blank" rel="noopener noreferrer">dunst site</a>
</p>  

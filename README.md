## deadd  
  
notification daemon/center for linux  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/deadd/raw/main/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install deadd
```  

Fedora Based:

```shell
yum install deadd
```  

Arch Based:

```shell
pacman -S deadd
```  

MacOS:  

```shell
brew install deadd
```
  
```shell
mv -fv "$HOME/.config/deadd" "$HOME/.config/deadd.bak"
git clone https://github.com/dfmgr/deadd "$HOME/.config/deadd"
```
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/Desktop_notifications" target="_blank" rel="noopener noreferrer">deadd wiki</a>  |  
  <a href="https://github.com/phuhl/linux_notification_center" target="_blank" rel="noopener noreferrer">deadd site</a>
</p>  

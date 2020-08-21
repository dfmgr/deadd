## deadd  
  
notification daemon/center for linux  
  
Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/dfmgr/deadd/raw/master/install.sh)"
```
Manual install:
  
requires:    
```
apt install deadd
```  
```
yum install deadd
```  
```
pacman -S deadd
```  
  
```
mv -fv "$HOME/.config/deadd" "$HOME/.config/deadd.bak"
git clone https://github.com/dfmgr/deadd "$HOME/.config/deadd"
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/Desktop_notifications" target="_blank">deadd wiki</a>  |  
  <a href="https://github.com/phuhl/linux_notification_center" target="_blank">deadd site</a>
</p>  

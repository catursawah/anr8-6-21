# RDP tools
- firefox
- remotecromedesktop
- multicontainer firefox
- autokey
- python3
- atbswp = https://github.com/RMPR/atbswp
- pyautogui

# Python
sudo apt install python3 python-is-python3 python3-pip python3-tk python3-dev git python3-dev python3-tk python3-setuptools python3-wheel python3-pip python3-wxgtk4.0  autokey-gtk autokey-common scrot
pip3 install pyautogui 
pip3 install selenium
pip3 install pytest

## install atbswp
sudo apt install git python3-dev python3-tk python3-setuptools python3-wheel python3-pip python3-wxgtk4.0 xdotool
git clone https://github.com/RMPR/atbswp.git && cd atbswp
python3 -m pip install pyautogui pynput --user
python3 atbswp/atbswp.py


# Good plans GPU
https://console.paperspace.com/
https://app.gpuhub.net/register?requestId=olardo
https://www.jovian.ai/  
https://jovian.ai/one10001/test
cannary gigle app
https://hub.binder.jovian.ml/user/one10001/terminals/1

## get mouse position

apt install -y xdotool
"""""""""""""""""""""""""""""""""""""
while [ 1 ];
do
    m=`xdotool getmouselocation|sed 's/x:\(.*\) y:\(.*\) screen:.*/\1, \2/'`
    echo $m
    if [ "$m" = "0, 0" ];
    then
        echo "top left"
    fi
    sleep 0.3
done

""""""""""""""""""""""""""""""""""""""""""""""""


# Chrome vs firefox
"Chrome + sessionbox"  < x1.6 < "firefox + multicontainer"
Chrome 76G <=> 144 
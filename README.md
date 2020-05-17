# UnbuntuTips
take notes for Ubuntu

## Desktop environment
- [Regolith](https://regolith-linux.org/)

## Teminal
- new teminal window and tag
new windows : ctrl + alt + T
new tag : shift + ctrl + T

- switch tag
alt + n

- change default path
asume changing to ~/text/program ,add codes below at the end of ~/.bashrc:
```
if [ -d ~/text/program ]; then
cd ~/text/program
fi
```

then reboot your PC.

## Toolkit

### Screenshot
- [Flameshot](https://github.com/lupoDharkael/flameshot)

### Screenrecord
- [OBS Studio](https://obsproject.com/)

Free and open source software for video recording and live streaming.

- [SimpleScreenRecorder](https://www.maartenbaert.be/simplescreenrecorder/)

SimpleScreenRecorder is a Linux program that I've created to record programs and games...

- [Peek](https://github.com/phw/peek)

Simple animated GIF screen recorder with an easy to use interface

### Keystroke visualizer

- [keymon](https://howtoinstall.co/en/ubuntu/xenial/keymon)

![](http://dl.iteye.com/upload/attachment/596149/83f8400f-a196-3db1-a0eb-3daba7556b17.png)

### Reference
- [工具箱-屏幕截图 (Toolkit-Screenshot)](https://zhuanlan.zhihu.com/p/76965810)
- [Best GIF Recorder Tools for Linux](https://itsfoss.com/best-gif-recorder-linux/)

## InputMethod-SogouPinying
1. Install Fcitx
```
sudo apt install fcitx
```
2. Install [Sogoupingyin](https://pinyin.sogou.com/linux/?r=pinyin)

3. Switch to Fcitx
```
im-config
```
4. Config Fcitx

add SogouPinyin


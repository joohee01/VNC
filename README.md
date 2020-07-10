# VNC

### 라즈베리파이 설정 변경
```
sudo raspi-config
```

### 라즈베리파이에서 vnc 연결
```
vncserver
```
### vncview에서 라즈베리파이 연결하기 
```
vncview 주소창에서 라즈베리파이를 연결한 'ip주소:1'을 적는다.
```
```
sudo raspi-config - 라즈베리파이 설정 변경

vncserver - 입력

vnc view에서 라즈베리파이 연결한 'ip주소:1'을 적는다

cp '복사할파일' '복사될위치'
ex) cp pir.py Downloads/pir.py
ex) cp pir.py /home/pi/Downloads/pir.py <절대경로

./는 현재 디렉토리를 의미한다.

rm '삭제할파일'
rm -rf  폴더 삭제 

vim cd2.py
sudo vim /boot/config.txt  <<< dtoverlay= pi3-disable-bt 편집하기
sudo systmectl disable hciuart
sudo reboot


텔레그램

pip3 install python-telegram-bot--upgrade

git clone https://github.com/python-telegram-bot/python-telegram-bot --recursive

python-telegram-bot/examples -> vim timerbot.py -> 토큰 입력
```

# Raspberry Pi datailmoitin projekti


## Haluatko testata koodia?  

Asenna seuraavat: 

```
sudo apt update
sudo apt install python-rpi.gpio python3-rpi.gpio
```

Cloonaa tämä git
```git
git clone https://github.com/Mixerboy24Tech/led-rpi4.git
```

Voit ajaa koodin seuraavalla tavalla.
```
python led.py
```

### Voit luoda siitä myös servicen (vapaaehtoinen)
```
sudo apt install tmux
sudo mv led.service /etc/systemctl/system/led.service
sudo systemctl daemon-reload
sudo systemctl enable led.service
sudo systemctl start led.service
```


### Ledin kytkeminen raspberryyn
![Preview](https://cdn.mb24.fi/Kuvat/vilkkuva_led_projekti1242.jpg)

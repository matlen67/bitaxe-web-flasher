[![](https://dcbadge.vercel.app/api/server/3E8ca2dkcC)](https://discord.gg/3E8ca2dkcC)

## Ihr nutzt einen LuckyMiner LV07, dann geht's hier weiter.
https://github.com/un-painted-org/bitaxe-web-flasher
<br><br>
## Achtung Warnung! Da ich das nun schon öffters gelesen habe
Solltet ihr an einen Bitaxe oder LuckyMiner LV06 ein 12V Netzeil anstelle des benötigten 5V Netzteils anschließen, ist mit höchster Wahrscheinlichkeit das Gerät sofort defekt. Entfernt zur Sicherheit alle LuckyMiner LV07 oder Laptop Netzeile von eurem Arbeitsplatz.  
<br>
# Bitaxe Web Flasher
Mit disem Bitaxe Webflasher kann der LuckyMiner LV06 direkt mit einer aktuellen AxeOS Factory-Firmware aus dem Browser geflasht werden. Die hier angebotenen esp-miner-factory-lv06 bin's enthalten die Konfiguration mit der Boardversion 0.11. Die Boardverson ist wichtig, da sonst das Mining nicht beginnt. 

https://matlen67.github.io/bitaxe-web-flasher/
<br><br>
## Benötigte Hardware:

USB to TTL Adapter: https://www.amazon.de/dp/B01CYBHM26?ref_=ppx_hzsearch_conn_dt_b_fed_asin_title_17


### Kabelverbindung:

LuckyMiner|TTL-Adapter
----------|-----------
   RX     |    TX     
   TX     |    RX     
   GND    |    GND    


<img src="https://github.com/user-attachments/assets/5d8fdfba-e75d-4d21-bf76-d0222ef9389e" alt="usb-to-ttl" width="500" height="500"> 



Um den Flashvorgang durchzuführen, muss der ESP32 in den Downloadmodus versetzt werden. Dazu auf der Unterseite der Leiterplatte den Boot-Taster (Bild 2) drücken und festhalten, danach auf der Oberseite einmal den Resettaster (Bild 3) betätigen. Nun kann der Boot-Taster wieder losgelassen werden. Wer sichergehen möchte das der Vorgang geklappt hat, kann den Webflasher verbinden und das Logging starten. Hält die Logausgabe mit 'waiting for download' an (Bild 1), ist der Vorgang geglückt.
Nachfolgend kann mit dem eigentlichen Flashvorgang begonnen werden.

### Bild 1 <br>
<img src="https://github.com/user-attachments/assets/c2b7e276-d748-4141-a0cd-6ff3c96edb03" alt="wait for download" width="600" height="300">
<br>
<br>

Bild 2|Bild 3
-----|-----
<img src="https://github.com/user-attachments/assets/d6c30460-eaa4-4726-82d3-84a9cbde348f" alt="IMG_20250212_203558l" width="400" height="400">|<img src="https://github.com/user-attachments/assets/5eec1b03-b0cd-4cb3-8938-036a6eb473eb" alt="IMG_20250212_203552" width="400" height="400">




The Bitaxe Web Flasher is the open source tool that provides you an easy solution to flash a factory file to you device.

## Flashing process

Simply connect your device, select the model and board version and click on flash.



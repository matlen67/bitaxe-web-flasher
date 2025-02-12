[![](https://dcbadge.vercel.app/api/server/3E8ca2dkcC)](https://discord.gg/3E8ca2dkcC)

# Bitaxe Web Flasher
Mit den Bitaxe Webflasher kann der LuckyMiner LV06 direkt mit einer aktuellen AxeOS Factory-Firmware aus dem Browser geflasht werden.
Die Factory.bin enthält die Config-Datei mit der Boardversion 0.11

https://matlen67.github.io/bitaxe-web-flasher/

Benötigte Hardware

USB to TTL Adapter: https://www.amazon.de/dp/B01CYBHM26?ref_=ppx_hzsearch_conn_dt_b_fed_asin_title_17


Verbindung:

LuckyMiner|TTL-Adapter
----------|-----------
   RX     |    TX     
   TX     |    RX     
   GND    |    GND    


![usb-to-ttl](https://github.com/user-attachments/assets/5d8fdfba-e75d-4d21-bf76-d0222ef9389e)

   
Um den Flashvorgang durchzuführen, muss der ESP32 in den Downloadmodus versetzt werden. Dazu auf der Unterseite der Leiterplatte den Boot-Taster drücken und festhalten, danach auf der Oberseite den Resettaster betätigen. Nun kann der Boot-Taster wieder losgelassen werden.
Wer sichergehen möchte das der Vorgang geklappt hat, kann den Webflasher verbinden und das Logging starten. Hält die Logausgabe mit Download an, ist der Vorgang geglückt.
Nachfolgend kann mit dem eigentlichen Flashvorgang begonnen werden.


The Bitaxe Web Flasher is the open source tool that provides you an easy solution to flash a factory file to you device.

## Flashing process

Simply connect your device, select the model and board version and click on flash.



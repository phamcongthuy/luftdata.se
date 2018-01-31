---
section: Bygg en mätstation
layout: docs
title: Kom igång
authors:
  - luftdaten.info
  - Hannes Ebner
pagination:
  next:
    name: Installera firmware
    link: /bygg/firmware/
lead: true
---

Monteringen är utformad så att alla kan bygga en mät&shy;station. Med endast 7 kopplings&shy;kablar och 2 bunt&shy;band gör du ett utvecklings&shy;kort och en sensor till en mät&shy;station.

Innehållet i dessa instruktioner är baserade på [motsvarande instruktioner på tyska på luftdaten.info](http://luftdaten.info/feinstaubsensor-bauen/).

![Bild på färdig mätstation](img/matstation.jpg)

Nedan finns en lista med alla delar som behövs, samt rekommenderade inköpsställen om man befinner sig i Sverige:

## Inköpslista

  * NodeMCU ESP8266 v3 (CPU & WLAN) [[Kjell](https://www.kjell.com/se/sortiment/el-verktyg/arduino/utvecklingskort/nodemcu-utvecklingskort-p87949), [Amazon](https://www.amazon.de/dp/B06Y1ZPNMS/)]
  * SDS011 (partikelsensor) [[AliExpress](https://www.aliexpress.com/wholesale?SortType=price_asc&shipCountry=de&SearchText=sds011&CatId=523)] (i Europa finns sensorn på [segor.de](http://www.segor.de) men det oklart om det levereras till Sverige)
  * DHT22 (temp. och luftfuktighet, *valfritt*) [[m.nu](https://www.m.nu/sensorer-matinstrument/dht22-temperature-humidity-sensor-extras), [Amazon](https://www.amazon.de/dp/B06XF4TNT9/)]
  * Kopplingskablar, ca. 20 cm, hona-hona [[Kjell](https://www.kjell.com/se/sortiment/el-verktyg/arduino/tillbehor/luxorparts-delbar-kopplingskabel-40-pol-hane-hane-p87901)]
  * USB-kabel, längd beroende på situation, USB 2.0 A hane - USB 2.0 micro hane, t.ex. platt utformning för fönstertätningar [[Conrad](https://www.conrad.se/USB-2.0-F%f6rl%e4ngningskabel-Renkforce-%5b1x-USB-2.0-A-hane-1x-USB-2.0-A-hona%5d-H%f6gflexibel-3-m-Svart.htm?websale8=conrad-swe&pi=1365367&amp;ci=SHOP_AREA_258249_0410105)]
  * USB-strömadapter (500 mA räcker) [[Kjell](https://www.kjell.com/se/sortiment/dator-natverk/datortillbehor/usb-tillbehor/usb-laddare/linocell-mini-usb-laddare-2-4-a-svart-p95717), [Biltema](http://www.biltema.se/sv/Kontor---Teknik/Mobilt/Kablar-och-laddare/Reseladdare-USB-2000036148/)]
  * Buntband [[Bauhaus](https://www.bauhaus.se/buntband-100-x-2-5-transparent-100-pack.html)]
  * Slang, invändig diameter 6 mm, längd ca. 20 cm [[Bauhaus](http://www.biltema.se/sv/Bat/VVS/Slang/Vattenslang-10-m-2000017745/?artId=15330)]
  * 2x avloppsböj som väderskydd (DN75 87°, Marley Silent HT) [[Bauhaus](https://www.bauhaus.se/ht-avloppsror-boj-87-o75mm.html)]
  
Har du hittat nån bra källa för en byggdel? Hör av dig till [info@luftdata.se](mailto:info@luftdata.se) så lägger vi till infon här.
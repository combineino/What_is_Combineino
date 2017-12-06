# What_is_Combineino? コンバインーノとは？
Arduino互換MPUといろんなシールドのコンバイン（結合）したい人のオープンソースハードウェア

Open Source Hardware Association
https://www.oshwa.org/

![image](https://github.com/combineino/What_is_Combineino/blob/master/OSHW%20Logo.jpg?raw=true)

オープンソース・ハードウェア（OSHW）基準書1.0
https://www.oshwa.org/definition/japanese/

オープンソースハードウェア　[wikipedia.](
https://ja.wikipedia.org/wiki/%E3%82%AA%E3%83%BC%E3%83%97%E3%83%B3%E3%82%BD%E3%83%BC%E3%82%B9%E3%83%8F%E3%83%BC%E3%83%89%E3%82%A6%E3%82%A7%E3%82%A2)

## ATmega
### MiniCore
https://github.com/MCUdude/MiniCore
#### Supported microcontrollers:
|              | ATmega328 | ATmega168 | ATmega88 | ATmega48 | ATmega8 |
|--------------|-----------|-----------|----------|----------|---------|
| **Flash**    | 32kB      | 16kB      | 8kB      | 4kB      | 8kB     |
| **RAM**      | 2kB       | 1kB       | 1kB      | 512B     | 1kB     |
| **EEPROM**   | 1kB       | 512B      | 512B     | 256B     | 512B    |
| **PWM pins** | 6         | 6         | 6        | 6        | 3       |

| 商品名                       | 販売価格          | URL                                          |
|------------------------------|-------------------|----------------------------------------------|
| ATMEGA48-20AU　TQFP32 20Mhz| 1個 ￥150（税込） | http://akizukidenshi.com/catalog/g/gI-08437/ |
| ATmega88V-10PU　DIP28　10Mhz | 1個 ￥150（税込） | http://akizukidenshi.com/catalog/g/gI-03655/ |
| ATMEGA8-16PU-ND　DIP28　16Mhz | 1個 ￥180（税込） | http://akizukidenshi.com/catalog/g/gI-02868/ |
| ATMEGA168P-20PU　DIP28　20Mhz | 1個 ￥200（税込） | http://akizukidenshi.com/catalog/g/gI-03033/ |
| ATMEGA328P-PU　DIP28　20Mhz  | 1個 ￥250（税込） | http://akizukidenshi.com/catalog/g/gI-03142/ |
| ATMEGA328P-AU　TQFP32 20Mhz | 1個 ￥280（税込） | http://akizukidenshi.com/catalog/g/gI-04386/ |
### ATmega328PB Testing
https://github.com/watterott/ATmega328PB-Testing/

### MightyCore
https://github.com/MCUdude/MightyCore
### Supported microcontrollers
|                  | mega1284 | mega644 | mega324 | mega164 | mega32 | mega16 | mega8535 |
|------------------|----------|---------|---------|---------|--------|--------|----------|
| **Flash**        | 128kB    | 64kB    | 32kB    | 16kB    | 32kB   | 16kB   | 8kB      |
| **RAM**          | 16kB     | 4kB     | 2kB     | 1kB     | 2kB    | 1kB    | 512B     |
| **EEPROM**       | 4kB      | 2kB     | 1kB     | 512B    | 512B   | 512B   | 512B     |
| **Serial ports** | 2        | 2       | 2       | 2       | 1      | 1      | 1        |
| **PWM pins**     | 8        | 6       | 6       | 6       | 4      | 4      | 4        |

| 商品名                       | 販売価格          | URL                                          |
|------------------------------|-------------------|----------------------------------------------|
| ATMEGA32U2-AUR TQFP32 16Mhz USB | 1個 ￥400（税込） | http://akizukidenshi.com/catalog/g/gI-06994/ |
| ATMEGA32U4-AUR TQFP44 16Mhz USB | 1個 ￥640（税込） | http://akizukidenshi.com/catalog/g/gI-09835/ |
| ATMEGA164P-20PU DIP40　20Mhz| 1個 ￥500（税込） | http://akizukidenshi.com/catalog/g/gI-02269/ |
| ATMEGA1284P-PU DIP40　20Mhz | 1個 ￥750（税込） | http://akizukidenshi.com/catalog/g/gI-04461/ |
| ATMEGA1284P-AU TQFP44 20Mhz | 1個 ￥780（税込） | http://akizukidenshi.com/catalog/g/gI-04416/ |

## MegaCore
https://github.com/MCUdude/MegaCore
### Supported microcontrollers:
|              | Mega2560 | Mega1280 | Mega640 | Mega2561 | Mega1281 | Mega128 | Mega64 | 
|--------------|----------|----------|---------|----------|----------|---------|--------|
| **Flash**    | 256kB    | 128kB    | 64kB    | 256kB    | 128kB    | 128kB   | 64kB   |
| **RAM**      | 8kB      | 8kB      | 8kB     | 8kB      | 8kB      | 4kB     | 4kB    |
| **EEPROM**   | 4kB      | 4kB      | 4kB     | 4kB      | 4kB      | 4kB     | 2kB    |
| **IO pins**  | 70/86 *  | 70/86 *  | 70/86 * | 54       | 54       | 53      | 53     |
| **PWM pins** | 15       | 15       | 15      | 8        | 8        | 7       | 7      |
| **LED pin**  | PB7      | PB7      | PB7     | PB5      | PB5      | PB5     | PB5    |

* 86 IO pins is only available with the AVR pinout selected
https://camo.githubusercontent.com/111cedfdd3ed144af35375382874e3c54b4faf8f/687474703a2f2f692e696d6775722e636f6d2f446652376172442e6a7067
(All variants - A, L, V) 

| 商品名                       | 販売価格          | URL                                          |
|------------------------------|-------------------|----------------------------------------------|
| ATMEGA128-16AU TQFP64 16Mhz | 1個 ￥800（税込） | http://akizukidenshi.com/catalog/g/gI-01116/ |
| ATMEGA128-16AU (0525)TQFP64  | 1個 ￥800（税込） | http://akizukidenshi.com/catalog/g/gI-09155/ |
| ATMEGA64-16AU TQFP64 16Mhz | 1個 ￥500（税込） | http://akizukidenshi.com/catalog/g/gI-01117/ |
| ATMEGA64L-8AU TQFP64 8Mhz | 1個 ￥600（税込） | http://akizukidenshi.com/catalog/g/gI-01118/ |
| ATMEGA64A-AU  TQFP64 16Mhz | 1個 ￥700（税込） | http://akizukidenshi.com/catalog/g/gI-04255/ |

## ATXmega
### XMega For Arduino
https://github.com/XMegaForArduino

AVR XMEGA マイクロコントローラー http://www.atmel.com/ja/jp/products/microcontrollers/avr/avr_xmega.aspx

1.6~3.3V 

## Supported microcontrollers:
* ATXMega64D4
* ATXMega32E5
* ATXMega128A1
* ATXMega128A1U
* CC0 ATXMega32E5 breakout
* Rock Solid XMega 128A

| 商品名                       | 販売価格          | URL                                          |
|------------------------------|-------------------|----------------------------------------------|
| ATXMEGA32D4-AUR TQFP44 32Mhz| 1個 ￥250（税込） | http://akizukidenshi.com/catalog/g/gI-06993/ |

## ATtiny
SpenceKonde/ATTinyCore
https://github.com/SpenceKonde/ATTinyCore
### Supported microcontrollers:
* ATtiny2313, 4313
* ATtiny24, 44, 84
* ATtiny25, 45, 85
* ATtiny261, 461, 861
* ATTiny48, 88

| 商品名                       | 販売価格              |                                              |
|------------------------------|-----------------------|----------------------------------------------|
| ATTINY85-20PU DIP8 20Mhz  | 1個 ￥160（税込）     | http://akizukidenshi.com/catalog/g/gI-09573/ |
| ATTINY861A-PU DIP20 20Mhz  | 1個 ￥220（税込）    | http://akizukidenshi.com/catalog/g/gI-04301/ |
| ATTINY2313-20PU DIP20 20Mhz | 1個 ￥230（税込）     | http://akizukidenshi.com/catalog/g/gI-01600/ |
| AT90S2313-10PC 10MHz(ATTINY2313互換）| 1個 ￥100（税込）     | http://akizukidenshi.com/catalog/g/gI-00026/ |
| ATTINY85-20SUR SOP8 20Mhz | 1個 ￥250（税込）     | http://akizukidenshi.com/catalog/g/gI-09574/ |

Arduino ATtiny/mega ピン割付表
http://make.kosakalab.com/web-archives/pins_arduino/

### with or without Optiboot bootloader
* ATTiny87, 167 
* ATTiny441, 841
* ATTiny1634
* ATTiny828

## 8pin AVRの活用
http://elm-chan.org/works/tiny/report.html 

| 商品名                       | 販売価格              |                                              |
|------------------------------|-----------------------|----------------------------------------------|
| ATTINY13A-PU DIP8 9.6Mhz   | 1個 ￥50（税込）      | http://akizukidenshi.com/catalog/g/gI-02911/ |
| ATTINY10 SOT6ピン 12Mhz 変換基板 | 1パック ￥150（税込） | http://akizukidenshi.com/catalog/g/gI-05174/ |
| AT90S2323-10PC DIP8 10Mhz  | 1個 ￥100（税込）     | http://akizukidenshi.com/catalog/g/gI-00027/ |

## AVR不明
| 商品名                       | 販売価格              |                                              |
|------------------------------|-----------------------|----------------------------------------------|
| AT90S4433-8PC DIP28 | 1個 ￥600（税込）     | http://akizukidenshi.com/catalog/g/gI-00270/ |
| AT90S8535-8 DIP40  8Mhz  | 1個 ￥700（税込）   | http://akizukidenshi.com/catalog/g/gI-00030/ |

# そのほか
スニペットとは、一般的には「切れ端」「断片」という意味の英語である。

AVRについてのページ
http://yueda.issp.u-tokyo.ac.jp/weda/avr/avrj.html

Adafruit Trinketを使ってHID（キーボード）を作る
http://b.denkizakana.com/2014/07/adafruit-trinkethid.html


Markdown Tables Generator
http://www.tablesgenerator.com/markdown_tables

プロジェクトの参考：Qiita [Arduinoを自作して量産して販売する](https://qiita.com/akichika/items/4c282c638b38681050d9)


## Licenses and Credits ライセンスとクレジット

### Arduinoのハードウエアのライセンスは、[Creative Commons](https://creativecommons.jp/licenses/) Attribution Share-Alike license(CC-BY-SA)です。

つまり、

* 著作権者のクレジット表記義務(BY)：原著作権者のクレジットを明記しなければいけません。
* 同一条件の継承義務(SA)：作品を改変・変形または加工した場合、その制作品をこの作品と同一の許諾条件でのみ、頒布することができます。

## Arduino Credits
https://www.arduino.cc/en/Main/Credits

Arduino is an open-source project founded by Massimo Banzi, David Cuartielles, Tom Igoe, Gianluca Martino, and David Mellis. It builds on the work of many people, projects, and institutions. This page attempts to summarize those contributions.

![image](https://cdn.arduino.cc/homepage/images/what_is-board.png)

Arduinoのハードウエアのライセンスより同一条件の継承義務(SA)ですので

### Combineino は Creative Commons License CC-BY-SA　とします。
<a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/deed.ja"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />
このハードウェアは <a rel="license" href="https://creativecommons.org/licenses/by/4.0/legalcode.ja">クリエイティブ・コモンズ 表示 - 継承 4.0 国際 ライセンス</a>の下に提供されています。

<a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/deed.ja">クリエイティブ・コモンズ BY-SA の要約</a>

クリエイティブ・コモンズ BY-SA の MarkDown https://github.com/idleberg/Creative-Commons-Markdown/edit/master/4.0/by-sa.markdown

以下は許可されます。
* 非営利の場合のみ使用許可(NC)はありません：この作品を営利目的で利用してもいいです。
* 改変の禁止(ND)はありません：作品を改変・変形または加工してもいいです。

 [easy labo](http://easylabo.com/) さんのブログ[Arduinoの商用利用](http://easylabo.com/2015/04/arduino/9065/)を参考にしました。


クリエイティブ・コモンズ・ライセンス (Creative Commons License)ライセンス付与のしかた
https://qiita.com/spiegel-im-spiegel/items/cc3d9cc46cc931b0e921

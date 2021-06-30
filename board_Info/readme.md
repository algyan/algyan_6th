[board_design]: img/algyan-6th.png
[board_sch]: img/algyan-6th-sch.png

# Board Info

## <a name="S0">0. Index</a>

* [1. Board Design](#S1)
* [2. Schematics](#S2)
* [3. Body of Materials](#S3)
  * [3-1. Parts List](#S3-1)
  * [3-2. Parts set A(お手軽)](#S3-2)
  * [3-3. Parts set B(手作りFULL)](#S3-3)

---

## <a name="S1">1. Board Design</a>

This board is designed by **Designed by EAGLE 9.6.2**.

* File(brd) : **algyan-6th-03.brd**
* File(gerber) : **algyan-6th-03_2021-04-03.zip**
* Image(png) : **img/algyan-6th.png**
    ![Board][board_design]

[↑ Back to Index](#S0)

---

## <a name="S2">2. Schematics</a>

* File(sch) : **algyan-6th-03.sch**
* File(pdf) : **algyan-6th-03.pdf**
* Image(png) : **img/algyan-6th-sch.png**  
    ![Board_sch][board_sch]

[↑ Back to Index](#S0)

---

## <a name="S3">3. Body of Materials</a>

### <a name="S3-1">3-1. Parts list</a>
|No.|部品名|種類|型番・値|個数|オンライン販売URL|
|:-:|:---:|:--:|:-----:|:----:|:---------------|
|1-1|ESP32-WROOM-32|U1||0～1|https://akizukidenshi.com/catalog/g/gM-11647/|
|1-2|ESP32-WROOM-32D|U1||0～1|https://akizukidenshi.com/catalog/g/gM-13318/|
|1-3|ESP32-WROOM-32E(16MB)|U1||0～1|https://akizukidenshi.com/catalog/g/gM-15675/|
|2|三端子レギュレータ|U2|NJM2845DL1|1|https://akizukidenshi.com/catalog/g/gI-11299/|
|3|USBシリアルIC|U3|FT231XS-R|1|https://akizukidenshi.com/catalog/g/gI-06713/|
|4|モータードライバーモジュール|U4|DRV8835|1|https://akizukidenshi.com/catalog/g/gK-09848/|
|5-1|ESP32-DevkitC|U5||1|https://akizukidenshi.com/catalog/g/gM-11819/|
|5-2|ESP32-DevKitC-32D|U5||1|https://akizukidenshi.com/catalog/g/gM-13628/|
|5-3|ESP32-DevKitC-32E(4MB)|U5||1|https://akizukidenshi.com/catalog/g/gM-15673/|
|6|チップ抵抗(2012)|R1、R2、R6、R7、R8、R9、R14、R16|10kΩ|2～8|https://www.sengoku.co.jp/mod/sgk_cart/detail.php?code=EEHD-57CE|
|7|チップ抵抗(2012)|R3、R4、R5、R10、R11、R12|100～1kΩ|3～6|https://www.sengoku.co.jp/mod/sgk_cart/search.php?cid=3329|
|8|チップ抵抗(2012)|R13、R15|5.1k/10kΩ|0、2|https://www.sengoku.co.jp/mod/sgk_cart/detail.php?code=EEHD-57C8<br>https://www.sengoku.co.jp/mod/sgk_cart/detail.php?code=EEHD-57CE|
|9|チップコンデンサ(3216)|C1、C2|22uF|2|https://akizukidenshi.com/catalog/g/gP-06038/|
|10|チップコンデンサ(2012)|C3、C5、C12|0.1uF|3|https://akizukidenshi.com/catalog/g/gP-13372/|
|11|チップコンデンサ(1608)|C4、C6、C7|0.01uF|3|https://akizukidenshi.com/catalog/g/gP-13387/|
|12|チップコンデンサ(3216)|C8、C9、C10、C11|0.1～22uF|0～4|https://akizukidenshi.com/catalog/c/c3216/<br>https://akizukidenshi.com/catalog/g/gP-06038/ (22uF)|
|13-1|チップダイオード|D1|RB751V40TE17|0～1|https://www.marutsu.co.jp/pc/i/2182237/|
|13-2|チップダイオード|D1|RB520S|0～1|https://akizukidenshi.com/catalog/g/gI-05566/|
|14|チップトランジスタ|T1、T2|2SC2712|2|https://akizukidenshi.com/catalog/g/gI-00761/|
|15-1|チップLED(赤色)|PWR、TXD、RXD、LED1、LED2、LED3|OSR50805C1C|0～6|https://akizukidenshi.com/catalog/g/gI-06419/|
|15-2|チップLED(緑色)|PWR、TXD、RXD、LED1、LED2、LED3|OSG50805C1C|0～6|https://akizukidenshi.com/catalog/g/gI-06423/|
|15-3|チップLED(オレンジ色)|PWR、TXD、RXD、LED1、LED2、LED3|OSO50805C1C|0～6|https://akizukidenshi.com/catalog/g/gI-06422/|
|15-4|チップLED(白色)|PWR、TXD、RXD、LED1、LED2、LED3|OSW50805C1C|0～6|https://akizukidenshi.com/catalog/g/gI-06425/|
|15-5|チップLED(青色)|PWR、TXD、RXD、LED1、LED2、LED3|OSB50805C1C|0～6|https://akizukidenshi.com/catalog/g/gI-06424/|
|15-6|チップLED(黄緑色)|PWR、TXD、RXD、LED1、LED2、LED3|OSG80805C1C|0～6|https://akizukidenshi.com/catalog/g/gI-06421/|
|15-7|チップLED(黄色)|PWR、TXD、RXD、LED1、LED2、LED3|OSY50805C1C|0～6|https://akizukidenshi.com/catalog/g/gI-06420/|
|16|フルカラーRGB LED|LED4|KPF-3236SURKMGKPBC|0～1|https://akizukidenshi.com/catalog/g/gI-12726/|
|17|チップタクトSW|SW1、SW2、SW3|TVAF06-A020B|3|https://akizukidenshi.com/catalog/g/gP-14888/|
|18|CdSセル|CDS1|GL5528(GL55xxシリーズ)|1|https://akizukidenshi.com/catalog/goods/search.aspx?search=x&keyword=GL55<br>https://akizukidenshi.com/catalog/g/gI-05859/|
|19|電子ブザー|BZ1|UGCM1205XP|1|https://akizukidenshi.com/catalog/g/gP-09800/|
|20|ピンヘッダ(40pin)|CN1、CN2、CN3、CN9||2、2、3、4pin|https://akizukidenshi.com/catalog/g/gC-00167/|
|21|microUSBコネクタ|CN4USB|ZX62-B-5PA(33)|1|https://akizukidenshi.com/catalog/g/gC-11183/|
|22|Groveコネクタ(I2C)|CN5、CN6、CN7、CN8|Female Header (4-pin/ 2mm)|4|https://www.sengoku.co.jp/mod/sgk_cart/detail.php?code=EEHD-4KKK|
|23|L型ピンヘッダ4Pin|CN10||4pin|https://akizukidenshi.com/catalog/g/gC-01627/|
|24|USB Type-CコネクタDIP化キット|CN11USB|AE-USB2.0-TYPE-C-5077R|0、1|https://akizukidenshi.com/catalog/g/gK-15426/|
|25|ピンヘッダ(40pin)|JP1、JP2||19、19pin|https://akizukidenshi.com/catalog/g/gC-00167/|
|26|シングルピンソケット (低メス)|U4、U5用ソケット|2212S-20SG-36|6、6、19、19pin|https://akizukidenshi.com/catalog/g/gC-03138/|

[↑ Back to Index](#S0)

---

### <a name="S3-2">3-2. Parts set A(お手軽)</a>
セット部品は(株)若松通商でオンライン購入可能です。  
  * https://wakamatsu.co.jp/biz/products/detail.php?product_id=38310051

|No.|部品名|種類|型番・値|個数|オンライン販売URL|
|:-:|:---:|:--:|:-----:|:----:|:---------------|
|5-3|ESP32-DevKitC-32E(4MB)|U5||1|https://akizukidenshi.com/catalog/g/gM-15673/|
|6|チップ抵抗(2012)|R8、R9|10kΩ|2|https://www.sengoku.co.jp/mod/sgk_cart/detail.php?code=EEHD-57CE|
|7|チップ抵抗(2012)|R10、R11、R12|220Ω|3|https://www.sengoku.co.jp/mod/sgk_cart/search.php?cid=3329|
|13-1|チップダイオード|D1|RB751V40TE17|0、1|https://www.marutsu.co.jp/pc/i/2182237/|
|13-2|チップダイオード|D1|RB520S|0、1|https://akizukidenshi.com/catalog/g/gI-05566/|
|16|フルカラーRGB LED|LED4|KPF-3236SURKMGKPBC|1|https://akizukidenshi.com/catalog/g/gI-12726/|
|17|チップタクトSW|SW3|TVAF06-A020B|1|https://akizukidenshi.com/catalog/g/gP-14888/|
|18|CdSセル|CDS1|GL5528(GL55xxシリーズ)|1|https://akizukidenshi.com/catalog/goods/search.aspx?search=x&keyword=GL55<br>https://akizukidenshi.com/catalog/g/gI-05859/|
|19|電子ブザー|BZ1|UGCM1205XP|1|https://akizukidenshi.com/catalog/g/gP-09800/|
|20|ピンヘッダ(40pin)|CN1、CN2、CN3、CN9||2、2、3、4pin|https://akizukidenshi.com/catalog/g/gC-00167/|
|22|Groveコネクタ(I2C)|CN5、CN6、CN7、CN8|Female Header (4-pin/ 2mm)|4|https://www.sengoku.co.jp/mod/sgk_cart/detail.php?code=EEHD-4KKK|
|25|ピンヘッダ(40pin)|JP1、JP2||19、19pin|https://akizukidenshi.com/catalog/g/gC-00167/|
|26|シングルピンソケット (低メス)(20pin)|U5|2212S-20SG-36|19、19pin|https://akizukidenshi.com/catalog/g/gC-00167/|

[↑ Back to Index](#S0)

---

### <a name="S3-3">3-3. Parts set B(手作りFULL)</a>
セット部品は(株)若松通商でオンライン購入可能です。  
  * https://wakamatsu.co.jp/biz/products/detail.php?product_id=38310052

|No.|部品名|種類|型番・値|個数|オンライン販売URL|
|:-:|:---:|:--:|:-----:|:----:|:---------------|
|1-2|ESP32-WROOM-32D|U1||0、1|https://akizukidenshi.com/catalog/g/gM-13318/|
|1-3|ESP32-WROOM-32E(16MB)|U1||0、1|https://akizukidenshi.com/catalog/g/gM-15675/|
|2|三端子レギュレータ|U2|NJM2845DL1|1|https://akizukidenshi.com/catalog/g/gI-11299/|
|3|USBシリアルIC|U3|FT231XS-R|1|https://akizukidenshi.com/catalog/g/gI-06713/|
|6|チップ抵抗(2012)|R1、R2、R6、R7、R8、R9、R14、R16|10kΩ|8|https://www.sengoku.co.jp/mod/sgk_cart/detail.php?code=EEHD-57CE|
|7|チップ抵抗(2012)|R3、R4、R5、R10、R11、R12|220Ω|6|https://www.sengoku.co.jp/mod/sgk_cart/search.php?cid=3329|
|8|チップ抵抗(2012)|R13、R15|10kΩ|2|https://www.sengoku.co.jp/mod/sgk_cart/detail.php?code=EEHD-57C8<br>https://www.sengoku.co.jp/mod/sgk_cart/detail.php?code=EEHD-57CE|
|9|チップコンデンサ(3216)|C1、C2|22uF|2|https://akizukidenshi.com/catalog/g/gP-06038/|
|10|チップコンデンサ(1608)|C3、C5、C12|0.1uF|3|https://akizukidenshi.com/catalog/g/gP-13372/|
|11|チップコンデンサ(1608)|C4、C6、C7|0.01uF|3|https://akizukidenshi.com/catalog/g/gP-13387/|
|13-1|チップダイオード|D1|RB751V40TE17|0～1|https://www.marutsu.co.jp/pc/i/2182237/|
|13-2|チップダイオード|D1|RB520S|0～1|https://akizukidenshi.com/catalog/g/gI-05566/|
|14|チップトランジスタ|T1、T2|2SC2712|2|https://akizukidenshi.com/catalog/g/gI-00761/|
|15-1|チップLED(赤色)|PWR、TXD、RXD、LED1、LED2、LED3|OSR50805C1C|2|https://akizukidenshi.com/catalog/g/gI-06419/|
|15-2|チップLED(緑色)|PWR、TXD、RXD、LED1、LED2、LED3|OSG50805C1C|2|https://akizukidenshi.com/catalog/g/gI-06423/|
|15-7|チップLED(黄色)|PWR、TXD、RXD、LED1、LED2、LED3|OSY50805C1C|2|https://akizukidenshi.com/catalog/g/gI-06420/|
|16|フルカラーRGB LED|LED4|KPF-3236SURKMGKPBC|1|https://akizukidenshi.com/catalog/g/gI-12726/|
|17|チップタクトSW|SW1、SW2、SW3|TVAF06-A020B|3|https://akizukidenshi.com/catalog/g/gP-14888/|
|18|CdSセル|CDS1|GL5528(GL55xxシリーズ)|1|https://akizukidenshi.com/catalog/goods/search.aspx?search=x&keyword=GL55<br>https://akizukidenshi.com/catalog/g/gI-05859/|
|19|電子ブザー|BZ1|UGCM1205XP|1|https://akizukidenshi.com/catalog/g/gP-09800/|
|20|ピンヘッダ(40pin)|CN1、CN2、CN3、CN9||2、2、3、4pin|https://akizukidenshi.com/catalog/g/gC-00167/|
|21|microUSBコネクタ|CN4USB|ZX62-B-5PA(33)|1|https://akizukidenshi.com/catalog/g/gC-11183/|
|22|Groveコネクタ(I2C)|CN5、CN6、CN7、CN8|Female Header (4-pin/ 2mm)|4|https://www.sengoku.co.jp/mod/sgk_cart/detail.php?code=EEHD-4KKK|
|24|USB Type-CコネクタDIP化キット|CN11USB|AE-USB2.0-TYPE-C-5077R|1|https://akizukidenshi.com/catalog/g/gK-15426/|
|25|ピンヘッダ(40pin)|JP1、JP2||19、19pin|https://akizukidenshi.com/catalog/g/gC-00167/|

[↑ Back to Index](#S0)

---

# miniDivide
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/01.jpg?raw=true" width = "600px" />

miniDivideは16mmの狭キーピッチを採用した分割型のキーボードです。  
小さく薄いため持ち運びやすく、特にスマートフォンとの相性は最高です。  
デスクの占有スペースも小さくて済むので普段遣いにも適しています。  
従来のキーボードよりキーの間隔が近いため、最小限の指の動きで文字を打鍵することが可能です。  

オプションでBLE Micro Proとコイン電池を搭載可能なため、PC・スマートフォン・タブレットへBluetoothでの接続が可能です。

## 部品

### キットに含まれているもの
|部品|個数|備考|
|:--|:--|:--|
|PCB|2||
|[ダイオード(表面実装型)](https://shop.yushakobo.jp/collections/all-keyboard-parts/products/a0800di-02-100)|38||
|[タクトスイッチ](https://akizukidenshi.com/catalog/g/gP-08081/)|2||
|[TRRSソケット](https://shop.yushakobo.jp/products/a0800tr-01-1?_pos=1&_sid=6aacd8367&_ss=r)|2||
|ゴム足シール|8||
|[チップ積層セラミックコンデンサー](https://akizukidenshi.com/catalog/g/gP-02151/)|2|BLE Micro Proでの無線化の際に使用。|
|[電源スイッチ(MK12C02)](https://ja.aliexpress.com/item/32798526843.html)|2|BLE Micro Proでの無線化の際に使用。|
|[HU1632](https://www.monotaro.com/p/8835/2765/)|2|BLE Micro Proでの無線化の際に使用。|
|短いネジ(M2 4mm)|8||
|長いネジ(M2 8mm)|18||
|短いスペーサー(M2 4mm)|4||
|長いスペーサー(M2 8mm)|2||
|ナット(M2)|14||



### ご自身で用意頂くもの

**※2023/08/13よりアクリルケースはキットに同梱されておりません。**  
Boothにて「miniDivide アクリルケース」を追加で購入頂くか、[遊舎工房のキーボードアクリルプレート
から「miniDivide (Choc v1キースイッチ用) - 2mm」](https://shop.yushakobo.jp/products/keyboard_acrylic_plate?variant=46424950604007)をお求めください。  
遊舎工房キーボードアクリルプレートから発注頂きますと、お好みのカラーを選択することも可能です。

|部品|個数|備考|
|:--|:--|:--|
|スイッチプレート|2|2mm厚アクリルプレート。|
|側面プレート|2|2mm厚アクリルプレート。|
|ボトムプレート|2|2mm厚アクリルプレート。|
|Pro Microプレート|2||
|[Kailh Choc v1キースイッチ](https://shop.yushakobo.jp/collections/all-switches/products/pg1350)|38||
|0.8uキーキャップ(16mm)|38|詳細は後述|
|[Pro Micro](https://talpkeyboard.net/?category_id=59e2ad48c8f22c3720001301)|2|動作確認済みのものは[こちら](https://talpkeyboard.net/items/62e24e6f8a0bd07fe2d38137)|

#### キーキャップ
キーキャップは0.8uピッチ(16mm未満)に対応したものをご利用ください。

[こちらの記事](https://e3w2q.github.io/10/)を参考にするとより良いかと思います。

以下は取り付け確認済みのキーキャップです。

[Choc 向け 挟ピッチ16mm 薄型キーキャップ（50個）  
<img src = "https://img.make.dmm.com/images/item/1273303/main_angled_R_20210609122258214_l.jpg" width="400px" />](https://make.dmm.com/item/1273303/)

[YKNキーキャップセット(Chocスイッチ 16x16mmキーピッチ用) v1.2  
<img src = "https://img.make.dmm.com/images/item/1280053/16x16choc2_20210221120518672_l.jpg" width="400px" />](https://make.dmm.com/item/1280053/)

### 無線化をする場合
|部品|個数|備考|
|:--|:--|:--|
|[BLE Micro Pro](https://shop.yushakobo.jp/products/ble-micro-pro)|2|Pro Microの代わりに取り付けることでBluetooth接続が可能。|


### お好みで
|部品|個数|備考|
|:--|:--|:--|
|[コンスルー](https://talpkeyboard.net/?category_id=5e451917cf327f255e6ae3ba)|4|BLE Micro Proを使う場合は13ピンのものを使用することもできます。|
|[LED(WS2812B](https://shop.yushakobo.jp/products/a0800ws-01-10)|10|アンダーグロウです。|

## 組み立て方

**組み立てる前に、全ての工程に目を通し、頭の中で組み立てるイメージをすると失敗を少なくスムーズに作業が進められます。**

### 1. PCBの表裏の確認

表  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3639.jpg?raw=true" width = "600px" />

裏  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3640.jpg?raw=true" width = "600px" />

**PCBはリバーシブルとなっ ており、左手側の表は右手側の裏面となります。**

左右を混同しないようにマスキングテープなどで表面に目印を付けておくとミスを減らすことができます。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3645.jpg?raw=true" width = "600px" />

### 2. ダイオードのハンダ付け

表面実装タイプのダイオードをハンダ付けします。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3647.jpg?raw=true" width = "600px" />

ダイオードは基板裏面に取り付けます。ダイオード端の白線が`▷|`マークの縦線と同じ向きになるようにしてください。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3648.jpg?raw=true" width = "600px" />

以下は別のキーボードでの作業動画となります。後述するダイオードのハンダ付けの仕方の行程がございますので、未経験の方は事前にご覧になるとより理解が深まるかと思います。  

https://user-images.githubusercontent.com/4215759/126895350-43ae4cd4-408b-4ff4-ab5c-2903e0420978.mov

ダイオード取付箇所に予備ハンダを行います。ハンダ付けの片方にハンダを溶かして載せておきます。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3649.jpg?raw=true" width = "600px" />

ピンセット等で、ダイオードを持ちながら予備ハンダを溶かしながらダイオードの片側をハンダ付けします。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3650.jpg?raw=true" width = "600px" />

もう片方もハンダ付けします。   
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3653.jpg?raw=true" width = "600px" />

片手分で19箇所、両手で38箇所にダイオードをハンダ付けします。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3654.jpg?raw=true" width = "600px" />

### 3. リセットスイッチの取り付け

Pro Microにファームウェアを書き込む際に押すリセットスイッチを取り付けます。  
リセットスイッチは[表面実装用タクトスイッチ(TVAF17-WEC-R)](https://akizukidenshi.com/catalog/g/gP-08081/)を使用します。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3655.jpg?raw=true" width = "600px" />

リセットスイッチは基盤裏側に取り付けます。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3656.jpg?raw=true" width = "600px" />

ダイオードと同様に予備ハンダをして取り付けます。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3657.jpg?raw=true" width = "600px" />

一箇所を予備ハンダを溶かしながらハンダ付けをします。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3658.jpg?raw=true" width = "600px" />

4箇所をハンダ付けすれば完了です。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3659.jpg?raw=true" width = "600px" />

### 4. ジャンパのハンダ付け

miniDivideのPCBはリバーシブルとなっているため、左手用右手用どちらも同じPCBで組み立てることができます。  
ジャンパは、PCBをリバーシブルで使う際の電気の流れを左手右手用に設定するものです。  
以上は余談ですので、理解しないまま作業を進めていただいても構いません。

赤丸で囲んだ場所がジャンパの位置です。PCBの**裏側**にあります。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3659_red.jpg?raw=true" width = "600px" />

基盤裏側のジャンパを赤丸の箇所と同様に白い枠内で囲まれたハンダ付け箇所同士をハンダで繋ぎます。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3660.jpg?raw=true" width = "600px" />

全部で4箇所のジャンパをハンダで繋げたら完了です。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3661.jpg?raw=true" width = "600px" />


### 5. Pro Microの取り付け

Pro Microを取り付けます。今回動作確認済みのものは[こちら](https://talpkeyboard.net/items/62e24e6f8a0bd07fe2d38137)です。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3667.jpg?raw=true" width = "600px" />

PCBはピンヘッダのハンダ付けとコンスルーに対応しております。  
通常のPro Microを利用する場合は12ピン、BLE Micro Proを利用する場合は13ピンを使うこととなります。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3668.jpg?raw=true" width = "600px" />

なお、左手と右手でPro Microを取り付ける際の面が異なりますので、ご注意ください。
下記は一般的なPro Microでの取り付けとなります。  
使用されるMCUによってはピンの配置が異なる可能性がありますので、PCBの表記とMCUの表記が合うかをご確認ください。

#### a. 左手

Pro Microの回路部分が底面に来るようにピンヘッダ・コンスルーを取り付けます。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3669.jpg?raw=true" width = "600px" />

#### b. 右手

Pro Microの回路部分が表面に来るようにピンヘッダ・コンスルーを取り付けます。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3672.jpg?raw=true" width = "600px" />

取り付けの際は、PCBの穴とPro Microの番号が合うように配置します。  
一番奥のBATとGNDはBLE Micro Pro用の穴ですので、通常のPro Microでは使用しません。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3676.jpg?raw=true" width = "600px" />

Pro Microとピンヘッダ or コンスルー、PCBを仮組みします。  
取り付け位置はPCBの表側です。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3678.jpg?raw=true" width = "600px" />

Pro Microとピンヘッダ or コンスルーをハンダ付けします。  
ピンヘッダを用いる場合は、PCBとピンヘッダを裏面からハンダ付けします。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3679.jpg?raw=true" width = "600px" />

### 6. ファームウェアの書き込み

ファームウェアのソースコードは[こちら](https://github.com/qmk/qmk_firmware/pull/19870)です。

Remapに対応しておりますので、[こちら](https://remap-keys.app/catalog/1zomPyGLGTcYW5gwoL6y/firmware)からファームウェアを書き込むことが可能です。
<img src = "https://user-images.githubusercontent.com/4215759/227790333-19d4aa23-8e11-4efb-a23b-55d9bf44172b.png" width = "600px" />

上述のファームウェアを書き込んだ後に、Remapを使うことでWebブラウザからキーマップの変更が可能です。
<img src = "https://user-images.githubusercontent.com/4215759/227790093-2f09359d-628a-477d-96a4-adc9cd498c86.png" width = "600px" />


### 7. バックライトLEDの取り付け

この項目は組み立て後に実施しても問題ありません。

バックライトLEDはWS2812Bを取り付け可能です。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3683.jpg?raw=true" width = "600px" />

リセットスイッチと同じ要領で、予備ハンダをした後にピンセットでLEDを持ちながら予備ハンダを溶かして1箇所を固定します。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3684.jpg?raw=true" width = "600px" />

LEDひとつにつき、4箇所をハンダ付けします。  
PCBに印字している番号が小さい順にハンダ付けをしていきます。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3690.jpg?raw=true" width = "600px" />

慣れるまでは、LEDを一つ取り付けるごとにUSBを繋いでLEDが点灯するかを確認すると着実に作業を進められます。  
LEDが店頭しない際は、キーマップに`RGB_MOD`を設定して、LEDのON/OFFを試行してください。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3691.jpg?raw=true" width = "600px" />

### 8. TRRSソケットの取り付け
左手と右手の接続にはTRRSソケットとTRRSケーブルを使用します。  
取り付け位置はPCBに「TRRS」と印字された箇所です.  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3692.jpg?raw=true" width = "600px" />

PCBの表面に載るようにTRRSソケットを取り付けます。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3693.jpg?raw=true" width = "600px" />

PCBを裏返してTRRSソケットの足が表面に出ているかを確認します。裏返す前にTRRSソケットをマスキングテープなどで固定すると作業がスムーズに進められます。  
全部で4本の足が出ていればOKです。足をハンダ付けします。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3694.jpg?raw=true" width = "600px" />

### 9. スイッチプレートとキースイッチの取り付け

下図右のスイッチプレートとキースイッチをPCBに取り付けます。  
スイッチプレートに保護シートが貼られている場合は、ピンセットで剥がしてください。剥がしづらい場合は水を少量含ませると剥がれやすくなるかと思います。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3722.jpg?raw=true" width = "600px" />

スイッチプレートをPCBの表面に置きます。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3723.jpg?raw=true" width = "600px" />

スイッチプレートにキースイッチを取り付け、PCBに挿します。一気に全てのキースイッチを挿すのではなく、数カ所にキースイッチを挿してハンダ付けをしてスイッチプレートとPCBを固定した後に残りのキースイッチを取り付けると作業がスムーズに進みます。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3725.jpg?raw=true" width = "600px" />

PCBの裏側からキースイッチの足が出ていることを確認します。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3726.jpg?raw=true" width = "600px" />

キースイッチの足とPCBをハンダ付けします。キースイッチでPCBとスイッチプレートを固定するので、キースイッチを押し込みながらハンダ付けすると、強固になります。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3728.jpg?raw=true" width = "600px" />

片手側で19個、両手で38個のキースイッチをハンダ付けします。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3729.jpg?raw=true" width = "600px" />

### 10. サイドプレート・ボトムプレートの取り付け

サイドプレートとボトムプレートをスイッチプレートに固定します。  
スイッチプレートと同様に保護シートが貼られている場合は剥がします。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3731.jpg?raw=true" width = "600px" />

短いネジ(5mm)と短いスペーサー(6mm)を取り出します。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3733.jpg?raw=true" width = "600px" />

Pro Micro左下(右手の場合は右下)の穴にスペーサーを載せます。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3734.jpg?raw=true" width = "600px" />

PCBを裏返して、スペーサーをネジで固定します。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3735.jpg?raw=true" width = "600px" />

短いネジ(5mm)と長いスペーサー(10mm)を取り出します。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3736.jpg?raw=true" width = "600px" />

スペーサーをボトムプレートに載せます。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3737.jpg?raw=true" width = "600px" />

ネジでスペーサーをボトムプレートに固定します。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3738.jpg?raw=true" width = "600px" />

長いネジ(8mm)と短いスペーサーを取り出します。(写真は長いネジのみ)  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3739_b.jpg?raw=true" width = "600px" />

長いネジを裏側から奥側のPro Micro横の穴に挿します。この時、ボトムプレート・サイドプレート・スイッチプレートを重ね合わせます。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3740.jpg?raw=true" width = "600px" />

表側から前述のネジにスペーサーを挿します。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3741.jpg?raw=true" width = "600px" />

長いネジ(8mm)とナットを取り出します。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3739.jpg?raw=true" width = "600px" />

キーボード外縁のネジ穴にネジを挿しナットで固定します。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3742.jpg?raw=true" width = "600px" />

裏面はこのようになっています。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3743.jpg?raw=true" width = "600px" />

### 11. Pro Microプレートの取り付け

前の項で取り付けたスペーサーに、Pro Microプレートを取り付けます。  
Pro Microプレートに保護シートが貼ってある場合は同様に剥がして下さい。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3744.jpg?raw=true" width = "600px" />

短いネジでスペーサーとPro Microプレートを固定します。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3745.jpg?raw=true" width = "600px" />

### 12. ゴム足の貼り付け

キーボードを机上に置いた際の滑り止めとしてゴム足シールを張ります。  
キーボード片側で4つゴム足シールを取り付けます。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3748.jpg?raw=true" width = "600px" />

以下は取り付け例になります。ご自身の打鍵スタイルにあわせて調整すると良いかと思います。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3749_b.jpg?raw=true" width = "600px" />

### 13. キーキャップの取り付け

キーキャップを取り付けます。  

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3779.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_4207.jpg?raw=true" width = "600px" />

### 14. BLE Micro Proで無線化する

**Pro Microで動作が確認できた後に実施することをオススメします。**  

必要な部品はBLE Micro Proに加えて
- 電池ホルダー(HU1632)
- 電源スイッチ
- 積層セラミックコンデンサ

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3927.jpg?raw=true" width = "600px" />

電源スイッチをPCB裏側に取り付けます。  
電源スイッチをPCBに載せた後に電源スイッチの足をハンダ付けします。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3928.jpg?raw=true" width = "600px" />

積層セラミックコンデンサをPCBの裏側に置きます。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3929.jpg?raw=true" width = "600px" />

ダイオードと同様に予備ハンダをして積層セラミックコンデンサをハンダ付けします。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3930.jpg?raw=true" width = "600px" />

電池ホルダーを取り出します。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3931.jpg?raw=true" width = "600px" />

電池ホルダーをPCBに挿す際に電池ホルダーの足の本数を参考に取り付ける向きを確認します。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3932.jpg?raw=true" width = "600px" />

電池ホルダーをPCBの表側に挿します。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3934.jpg?raw=true" width = "600px" />

電池ホルダーをハンダ付けする前に、表面からマスキングテープで固定すると作業がスムーズに行なえます。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3935.jpg?raw=true" width = "600px" />

電池ホルダーの足がPCBの裏側から出ていることを確認します。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3937.jpg?raw=true" width = "600px" />

電池ホルダーの足をハンダ付けします。ハンダが盛られすぎると、アクリルケースが浮いてしまうことがあるので、なるべく薄めにハンダ付けすると良いかと思います。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3939.jpg?raw=true" width = "600px" />

コイン電池(CR1632)を取り付けて完成です。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3948.jpg?raw=true" width = "600px" />

config.jsonやkeymapは[こちら](https://github.com/sekigon-gonnoc/BLE-Micro-Pro/tree/master/AboutDefaultFirmware/keyboards/takashicompany/minidivide)に公開しております。

上記のconfig.jsonを使用する場合は
左手側が親機(PCとBluetooth接続をする & 子機との接続も行う)となります。

1. 左手側(親機)のBLE MICRO PROをPCにUSBで接続し、 `CONFIG.JSN`に[`takashicompany_minidivide_master_left_config.json`](https://github.com/sekigon-gonnoc/BLE-Micro-Pro/blob/master/AboutDefaultFirmware/keyboards/takashicompany/minidivide/takashicompany_minidivide_master_left_config.json)のテキストを上書きして保存する。
1. 右手側(子機)のBLE MICRO PROをPCにUSBで接続し、 `CONFIG.JSN`に[`takashicompany_minidivide_slave_right_config.json`](https://github.com/sekigon-gonnoc/BLE-Micro-Pro/blob/master/AboutDefaultFirmware/keyboards/takashicompany/minidivide/takashicompany_minidivide_slave_right_config.json)のテキストを上書きして保存する。
1. 左手のminiDivideをBluetoothでPCと接続する
1. 左手のminiDivideをBluetoothで右手のminiDivideと接続する

という手順で進めると左右間とPCで無線接続が可能になるかと思います。  
[BLE Micro Pro用のQMK Configurator](https://sekigon-gonnoc.github.io/qmk_configurator)を用いて、接続状態などを確認しながらやると、作業が進めやすくなるかと思います。

## トラブルシューティング

### BLE Micro Proを搭載した右手側のminiDivideが反応しない場合

1. BLE Micro Pro(Pro Micro)の表裏があっているかを確認する。左手と右手で取り付けの際の表裏が異なります。
1. miniDivideにPro Microを取り付けUSBでPCと接続して、各種キーが入力できるかを確認する。
1. 接続に成功している左手側のBLE Micro Proを右手側に取り付けて動作するかを確認する。
1. BLE Micro Proの[ブートローダーを最新版にする。](https://sekigon-gonnoc.github.io/BLE-Micro-Pro-WebConfigurator/#/update/bootloader)
1. BLE Micro Proの[アプリケーションを最新版にする。](https://sekigon-gonnoc.github.io/BLE-Micro-Pro-WebConfigurator/#/update/application)
1. [ペアリングを確認する](https://sekigon-gonnoc.github.io/BLE-Micro-Pro/#/getting_started?id=%e3%83%9a%e3%82%a2%e3%83%aa%e3%83%b3%e3%82%b0%e3%81%99%e3%82%8b)

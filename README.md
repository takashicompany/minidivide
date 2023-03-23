# miniDivide

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
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3972.jpg?raw=true" width = "600px" />

取り付けの際は、PCBの穴とPro Microの番号が合うように配置します。  
一番奥のBATとGNDはBLE Micro Pro用の穴ですので、通常のPro Microでは使用しません。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3976.jpg?raw=true" width = "600px" />

Pro Microとピンヘッダ or コンスルー、PCBを仮組みします。  
取り付け位置はPCBの表側です。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3978.jpg?raw=true" width = "600px" />

Pro Microとピンヘッダ or コンスルーをハンダ付けします。  
ピンヘッダを用いる場合は、PCBとピンヘッダを裏面からハンダ付けします。
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3679.jpg?raw=true" width = "600px" />

### 6. ファームウェアの書き込み

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

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
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_2729.jpg?raw=true" width = "600px" />

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
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3940.jpg?raw=true" width = "600px" />

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

積層セラミックコンデンサをPCBの裏側の置きます。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3929.jpg?raw=true" width = "600px" />

ダイオードと同様に予備ハンダをして積層セラミックコンデンサをハンダ付けします。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3930.jpg?raw=true" width = "600px" />

電池ホルダーを取り出します。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.3931jpg?raw=true" width = "600px" />

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

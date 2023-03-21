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

PCBはコンスルーに対応しております。  
<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_3668.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/minidivide/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

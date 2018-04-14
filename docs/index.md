不定期に開催しているマインクラフトサーバーです。  

■サーバー情報
* サーバーURL: [kouta.tk](kouta.tk)  
* Discordサーバー: [https://discord.gg/Q54en](https://discord.gg/Q54en)

■その他連絡先等
* Twitter: [@k0ta0uchi](https://twitter.com/k0ta0uchi)
* ニコニココミュ: [Rフェイススタジオ](http://com.nicovideo.jp/community/co2576092)
* YouTube: [Rフェイススタジオ](https://www.youtube.com/channel/UCDktbMSBDBmMp1k_DJGaY6A)
* Twitch: [k0ta0uchi](https://www.twitch.tv/k0ta0uchi)  
  

# Enigmatica 2
「Enigmatica 2」はMinecraft PC（Java）版のMODパックです。
[https://minecraft.curseforge.com/projects/enigmatica2](https://minecraft.curseforge.com/projects/enigmatica2)

## 導入方法1
導入方法1では、Twitch（ゲーム特化型動画配信サービス）アプリが必要です。下記のURLからダウンロードしてインストールしてください。  
[https://app.twitch.tv/download](https://app.twitch.tv/download)

また、Twitchアプリを使用するにはアカウントが必要になります。
まだ取得していない場合は、下記のURLの右上にある「登録」をクリックして取得してください。  
[https://www.twitch.tv/](https://www.twitch.tv/)

Twitchアプリを起動し、Modsタブを開きます。
![twitchui_2018-04-14_13-38-49](https://user-images.githubusercontent.com/1085968/38764400-3c84b8e6-3fe9-11e8-9ca5-b844da8f221c.png)

左上の方にMinecraftが表示されているはずなので、クリックします。（所持しているゲームによっては異なります）

すると下記のようなメニューが出てくるので、「すべてのModパックを参照する」をクリックします。
![twitchui_2018-04-14_13-41-09](https://user-images.githubusercontent.com/1085968/38764413-8336635c-3fe9-11e8-9d47-4546ca6735d6.png)


MODパック一覧がずらーっと出てくるので、検索テキストボックスに「Enigmatica 2」と入力します。一覧に「Enigmatica 2」があるのでクリックするとインストールが開始されます。

先程のメニューから、マイModパックを選択すると、今導入しているModパック一覧が表示されます。
![twitchui_2018-04-14_13-44-19](https://user-images.githubusercontent.com/1085968/38764442-f5700946-3fe9-11e8-98f8-80b08aabe3e3.png)

ここで「Enigmatica 2」を選択し、再生をクリックすると導入された状態で起動します。

### マインクラフトの設定
Twitchアプリからマインクラフトの設定を行いたい場合、Twitchアプリの左上のアイコンをクリックし、「ファイル」→「設定」と選択します。

![twitchui_2018-04-14_13-47-44](https://user-images.githubusercontent.com/1085968/38764465-6efe8ec2-3fea-11e8-904f-5593eea905d9.png)

左側のメニューよりMinecraftを選択すれば、マインクラフトの設定が行なえます。

![twitchui_2018-04-14_13-49-05](https://user-images.githubusercontent.com/1085968/38764477-d5317e20-3fea-11e8-830a-b91ff19c9412.png)

ここでは解像度や、使用メモリなど様々な設定が行えますが、「Enigmatica 2」を遊ぶ場合、4GB以上のメモリが必要になるので、必ず設定しておきましょう。


## 導入方法2
Twitchアプリを導入したくない場合は、この方法を使用してください。
まず、MODパックのデータをZIP化したファイルが必要になります。

下記のURLより、Discordサーバーに接続してください。  
[https://discord.gg/Q54en](https://discord.gg/Q54en)

ここに、MODデータへリンクが貼られています。

ダウンロードが完了したら、まずマインクラフトランチャーを起動し、新しいプロファイルを作成します。

![minecraft_2018-04-14_14-09-58](https://user-images.githubusercontent.com/1085968/38764624-a44387ce-3fed-11e8-8cdb-ad9b172d182b.png)

新規作成をクリックし、マインクラフトのバージョンを選択します。  
バージョンは1.12.2、Forgeは14.23.2.2611以上です。

![code_2018-04-14_14-11-34](https://user-images.githubusercontent.com/1085968/38764631-d1a6764a-3fed-11e8-9ff3-7b18c1e66cda.png)


### Forgeのバージョン
導入しているForgeのバージョンが、「14.23.2.2611」以上であるかどうかを確認してください。  
バージョンが古い場合は、再度下記のサイトからForgeをダウンロードし、導入してください。  
[https://files.minecraftforge.net/](https://files.minecraftforge.net/)


### ゲームディレクトリ
場所はどこでも構いませんが、他のデータを上書きしないようなフォルダを作成し、設定してください。  
このフォルダはのちのち使用するので覚えておきましょう。

### JVMの引数
ここで使用メモリの設定を行います。下記の設定を入力してください。  
``-Xms4G -Xmx4G``

また、私が個人的に設定しているオプションは下記のとおりです。  
``-Xms4G -Xmx4G -client -XX:MetaspaceSize=512M -XX:MaxMetaspaceSize=512M -XX:+UseConcMarkSweepGC -XX:+CMSIncrementalMode -XX:+AggressiveOpts -XX:+DisableExplicitGC -XX:+UseBiasedLocking -XX:+UseFastAccessorMethods -XX:+UseTLAB -XX:+UseLargePages -XX:-UseGCOverheadLimit -XX:+UnlockExperimentalVMOptions -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=16M -XX:+UseNUMA -XX:+CMSParallelRemarkEnabled -XX:MaxTenuringThreshold=15 -XX:GCPauseIntervalMillis=150 -XX:+UseAdaptiveGCBoundary -XX:SurvivorRatio=8 -XX:TargetSurvivorRatio=90 -Dfml.ignorePatchDiscrepancies=true -Dfml.ignoreInvalidMinecraftCertificates=true -XX:+UseCompressedOops -XX:+OptimizeStringConcat -XX:ReservedCodeCacheSize=2048m -XX:+UseCodeCacheFlushing -XX:SoftRefLRUPolicyMSPerMB=10000 -XX:ParallelGCThreads=10``

使用しているJavaのバージョンによっては使用できなかったりするので、適宜削除してください。

設定を行ったら「保存」ボタンのクリックを忘れずに。私も何回か忘れてひどい目にあってます。
    
### MODデータの上書き
ここまで設定できたらまず起動します。起動し終わったらマインクラフトを閉じます。  
先程設定したゲームディレクトリを開きます。  
DiscordサーバーからダウンロードしてきたMODデータを解凍します。  
このとき、mods以下ではなく、設定したゲームディレクトリ以下で回答するようにしてください。mods以外のデータも含まれているためです。

### 起動確認
MODが200以上含まれるため、相当時間がかかります。起動開始したらコーヒーでも淹れに生きましょう。


## マルチプレイに参加するには
マインクラフトが起動したら、Multiplayを選択します。  
サーバーの選択画面が表示されるので、右下にある「Add Server」をクリックします。  
するとこのような画面が出てきます。  
![javaw_2018-04-14_14-33-45](https://user-images.githubusercontent.com/1085968/38764814-e17eb0ac-3ff0-11e8-8133-c3dec03f0b9c.png)

Server Addressの部分に「kouta.tk」と入力します。  
入力が終わったら「Done」をクリックし、サーバー選択画面に戻ります。

![javaw_2018-04-14_14-41-15](https://user-images.githubusercontent.com/1085968/38764862-f2231a6e-3ff1-11e8-86d1-57e2ecc4c9a6.png)

こんな感じで表示されていれば成功です！！ログインしてみましょう！！！
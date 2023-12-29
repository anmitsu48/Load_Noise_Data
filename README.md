# Load_Noise_Data
このレポジトリは私が取得した道路騒音に関するデータを公開します。

NoiseMeter_Excel_Data の中に、騒音計で取得したデータを整理したExcelファイルをアップロードしています。

## 計測条件
本レポジトリで公開しているデータは、私が住んでいるマンション（川崎市内）のベランダに計測機器を設置して取得したものです。
私の住んでいるマンションは国道1号線から100m程度離れた場所にあり、私の部屋は10階以上あるマンションの6階以上にあります。
私の住んでいるマンションの近くの国道1号線のエリアでの自動車騒音（昼間）は、以下のサイトで50～65dB（2019年）です。
  - https://tenbou.nies.go.jp/gis/monitor/?map_mode=monitoring_map&field=8.

計測時は下の写真のように三脚に騒音計とボイスレコーダーを取り付けたものを使用しました。
三脚、騒音計、ボイスレコーダーは全てAmazonで購入しました。
  - SLM-25（ https://www.gainexpress.com/products/slm-25 ）
  - ボイスレコーダーAi-16（Amazon：https://www.amazon.co.jp/gp/product/B0BKLCFT92/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1 ）

![三脚設置環境](https://github.com/anmitsu48/Load_Noise_Data/assets/58377673/9c6f2eeb-1483-44fc-9b40-3164eda51585)

騒音計とボイスレコーダーの細かな設定を箇条書きでまとめると以下の通りです。
  - 騒音計の高さ：ウインドスクリーン（スポンジの部分）の部分が床面から125cm。
  - 騒音計はFast、A特性に設定。
  - 騒音計の記録は「10秒に1回の記録」で設定（騒音計対応のソフトを使用）
  - ボイスレコーダーの感度：7段階で設定できるうちの一番小さなものに設定。
  - ボイスレコーダーのノイズキャンセリング機能：OFF
  - ボイスレコーダーのサンプリング周波数：48kHz（PCにデータを取り込み、MATLAB（プライベートでライセンスの購入をしたもの）で確認しています）

※ 騒音計とボイスレコーダーのデータをアップロードしていますが、時刻同期は完璧にはできていません。
ちなみに、同期方法は、騒音計とボイスレコーダーの両者の録音開始ボタンを押した後に「アー」と大声で叫んだタイミングをそろえるようにしているだけです。
騒音計が10秒に1回の記録設定のため、最大で10秒の差があると思います。正直、いくつかの波形を確認していると、5, 6秒の差はあると個人的には思っています。

## Noteでの記事公開
本レポジトリで公開しているデータに関連する記事をnoteで公開しています。
  - 2023/12/23（午前中）の計測結果について：https://note.com/anmitsu48/n/nd7bce4799844?sub_rt=share_pw

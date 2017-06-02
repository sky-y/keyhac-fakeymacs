## これは何？

- Windowsの上で、KeyhacというツールでEmacs風キー操作を実現するための設定です
    - 本体は [Keyhac 公式サイト](https://sites.google.com/site/craftware/keyhac-ja) からダウンロードして適当な場所に展開します
    - 本体(keyhac.exe)のあるフォルダに、このリポジトリの「config.py」を置きます
- 設定の元ネタ
    - [Windows の操作を emacs のキーバインドで行うための設定 （Keyhac版） - NTEmacs @ ウィキ - アットウィキ](https://www49.atwiki.jp/ntemacs/pages/25.html)
    - 上記では、この設定のニックネームを「fakeymacs」としています


## 補足

- CapsLockキーへのCtrlキーの割当て
    - 私は [KeySwap](http://www.vector.co.jp/soft/winnt/util/se228667.html) を併用しています。
    - config.py で `side_of_ctrl_key` 変数を `R`（右）とし、CapsLockキーに右Ctrlキーを割り当ています。こうすると、ユーザから見たキー割り当てを下記の通りにできます：
        - CapsLock: KeyhacのCtrl（Emacs風のキー操作）
        - 左Ctrlキー: Windowsショートカットキー（既定）のCtrlと同じ

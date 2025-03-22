# **Airaw**

**Airaw** は、CarPlay に拡張機能を追加するための調整です！
この調整により、CarPlay にさらなるカスタマイズ機能が追加されます。通常、CarPlay のホーム画面は 2×4 のアイコングリッドをサポートし、最大 8 つのアイコンを表示できます。しかし、一部のユーザーにとってはこれでは不十分かもしれません。そんな時に **Airaw** が役立ちます！
詳細は、[iDownloadBlog レビュー][2]又は[ONE jailbreak レビュー][12]をご確認ください。

**Airaw** は CarPlay を自由にカスタマイズできるように設計されています。

- アイコンのカスタマイズ
- 壁紙の変更
- ステータスバーのカスタマイズ
- ウィジェットの追加

これらの機能を活用し、あなた好みの CarPlay を実現できます！

<div style="height: 300px;">
    <img class="screenshot" src="https://dcsyhi1998.github.io/icons/Airaw/demo0.png" id="screenshot0">
</div><br>

---

## **💰 サポートのお願い**

**Airaw の機能が気に入った場合は、[PayPal](https://www.paypal.me/DevDcsyhi) での寄付を歓迎します。**
もし寄付が難しい場合は、**Twitter をフォローしてサポート**してください！
フォローや寄付が増えれば、開発のモチベーションが上がり、より多くの機能を追加できます。

👉 **Twitter:** [@linux_n1](https://twitter.com/linux_n1)

---

## **📌 含まれる機能**

### **🔹 アイコンレイアウト**

- 透明アイコンの生成（CarBridge 必須）
- CarPlay のアイコン行数を 2 ～ 4 に変更
- CarPlay のアイコン列数を 4 ～ 6 に変更
- CarPlay のアイコンサイズを変更
- ダッシュボードアプリアイコンのオフセット調整（上 / 下 / 左 / 右）
- アイコンラベルの非表示
- ラベル背景の非表示
- アイコンテキストの色変更
- ホーム画面のドットを非表示
- フルスクリーンアプリの選択（CarBridge 必須）
- アイコンバッジ色の変更
- 表示アイコンのフォントサイズの変更

### **🎨 壁紙**

- 壁紙またはスライドショーの選択
- CarPlay の壁紙を自由に変更（GIF 対応）
- スライドショー用の複数壁紙を追加可能
- 壁紙のサイズ調整（デフォルト / フィット）

### **📊 ステータスバー**

- カスタムステータスバーの有効化
- 日付・時間のフォーマット変更
- 時間に秒の表示を有効化
- ステータスバーの位置変更（上 / 下 / 左 / 右）
- 天気アイコンの表示
- 気温の表示
- バッテリーアイコンの表示
- Bluetooth 接続時のバッテリーアイコン非表示
- スプラッシュスクリーンの削除
- Wi-Fi / 時間 / バッテリー / DND / LTE などの色変更
- ステータスバー背景色のカスタマイズ
- ホームボタンのアイコン色変更
- ホームボタンをお好みの画像に変更

### **📦 ウィジェット**

- ウィジェットの追加
- ウィジェットのサイズ変更
- ウィジェットの位置変更
- 使用する API の選択

### **⚒️ その他の機能**

- CarPlay スプラッシュスクリーンの削除
- キーパッドのアクセス制限無効化
- 純正マップのダークモード
- CarPlay の角の黒枠線削除
- CarBridge をインストールしたユーザー向けにアプリをフルスクリーン化

---

## **🔨 開発者向け Airaw API**

Airaw API は、CarPlay 用のウィジェットの作成を容易にするのに役立ちます。\
詳細については、[Airaw API][4]ページをご覧ください。
さらに詳しく知りたい場合は、[Twitter DM][1] でお問い合わせください。

---

## **🚀 今後追加予定の機能**

✅ **実装済み**

- 壁紙変更時のリアルタイム更新
- ステータスバーのカスタマイズ
- ステータスバーに天気情報を表示
- フルスクリーンアプリの表示([デモ][3])
- ステータスバーの色変更([デモ][9])
- iOS16 で HTML ウィジェット対応
- ノッチ付き端末でのフルスクリーン動画再生対応([デモ][8])

🛠 **開発予定**

- **CarPlay のスプリットビュー対応**

---

## **❓ FAQ**

Q\. **天気アイコンが正しく表示されない場合**\
A\. こちらの[ツイート][6]を確認してください。

Q\. **アプリが正しくフルスクリーン表示されない**\
A\. iOS14 の場合はこちらの[ツイート][5]を確認してください。\
A\. iOS15 - iOS16 の方はこちらの[ツイート][10]を確認してください。

Q\. **ウィジェットのダウンロード方法を教えてください**\
A\. ウィジェットは開発元が提供するリポジトリからダウンロードしてください。

Q\. **ウィジェットの作成方法を教えてください**\
A\. ウィジェットは HTML で作成できます。必要に応じて、Airaw API が提供するデバイス情報を使用してください。

Q\. **手動でウィジェットを追加するには？**\
A\. Filza から以下の 3 つのディレクトリのいずれかを作成します。

- /var/mobile/Library/SBHTML/
- /var/mobile/Library/iWidgets/
- /var/mobile/Library/Widgets/Universal/

各ウィジェットに対応する HTML ファイルは以下の通りです。

- SBHTML: Wallpaper.html
- iWidgets: Widget.html
- Universal: index.html

---

## **📱 互換性**

- **対応 iOS:** iOS14 - 16.7
- **対応 CPU:** arm64 & arm64e

### テスト済みデバイスと調整(Tweak)

✅ **テスト済みデバイス**

- iPhone 6s iOS 14.7.1 (checkra1n - Rootful)
- iPhone Xs Max iOS 14.4 (unc0ver - Rootful)
- iPhone Xs iOS 15.0.1 (Dopamine - Rootless)
- iPhone 7 iOS 15.7.5 (palera1n - Rootless)
- iPhone 14 Pro Max iOS 16.0.2 (Dopamine - Rootless)

✅ **テスト済み調整**

- CarBridge

---

## **🙏 特別な感謝**

### Airaw のアイコンとバナーを作成していただいた[Ouni’sDesigns](7)に感謝いたします。

---

## **💰 返金ポリシー**

- **購入後 24 時間以内であれば、適切な理由がある場合に限り返金を許可します。**
- **不適切なリクエスト（暴言・嫌がらせ）は拒否されます。**
- **クラッシュやバグが原因の返金は、詳細な説明が必要です。**

---

## **📩 Feedback & Bug Reports**

📧 **Email:** <dcsyhi1998@gmail.com>\
🐦 **Twitter:** [@linux_n1](https://twitter.com/linux_n1)

[1]: https://twitter.com/intent/follow?screen_name=linux_n1
[2]: https://www.idownloadblog.com/2021/06/11/airaw/
[3]: https://twitter.com/linux_n1/status/1486356268180643841?s=20&t=GNpcgOkSLXcmHSI3L-QFOg
[4]: https://dcsyhi1998.github.io/airawapi
[5]: https://twitter.com/linux_n1/status/1479025725663776769?s=20&t=6X2EsGT3w5_1RMqI-DqXqw
[6]: https://twitter.com/linux_n1/status/1470751948454625282?s=20&t=6X2EsGT3w5_1RMqI-DqXqw
[7]: https://twitter.com/OuniDesigns
[8]: https://twitter.com/linux_n1/status/1755251568973344821
[9]: https://x.com/linux_n1/status/1762098211949559980
[10]: https://x.com/linux_n1/status/1762123372518096933
[11]: https://x.com/linux_n1/status/1763546509633855912
[12]: https://onejailbreak.com/blog/airaw-tweak/

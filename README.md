# Hanemy Light Homepage v0.7

Hanemy（ハネミー）の公開β向け軽量ホームページです。

## 今回の更新

- 新しいブランドロゴを反映
- 背景透過版の横長ロゴを追加
- 背景透過版のアイコンを追加
- 背景透過版のマスコットを追加
- ホームページ内の表示画像を新ブランド素材に更新

## 収録ファイル

- `index.html`：ホームページ本体
- `assets/logo-horizontal-transparent.png`：背景透過の横長ロゴ
- `assets/logo-icon-transparent.png`：背景透過のアイコン
- `assets/mascot-transparent.png`：背景透過のマスコット
- `favicon.png`：ブラウザ用アイコン
- `icon-192.png` / `icon-512.png`：PWA用アイコン
- `LICENSE`：ライセンス

## 目的

このホームページは、本格的なLPではなく、公開βに添える軽い公式ページです。

主な目的：

- ハネミーが何のアプリか一瞬で伝える
- アプリ本体へ誘導する
- 今後、問い合わせやフィードバック導線を追加する土台にする

## アプリリンク

```text
https://figiecc.github.io/hanemy/
```

## ブランド表記

- `Hanemy™` を使用
- `®` は使わない


## v0.6.1 hotfix

- ロゴ画像の背景に見えていたチェック柄を除去
- ホームページで使うロゴ・アイコン・マスコット画像を差し替え


## v0.6.2 favicon hotfix

- ブラウザタブに表示される `favicon.png` を新ブランドアイコンへ差し替え
- `icon-192.png` / `icon-512.png` も新ブランドアイコンへ差し替え
- favicon参照にキャッシュ対策のクエリを追加


## v0.7 mailto contact

- Googleフォームを使わず、ホームページ内に問い合わせ・フィードバック欄を追加
- 入力内容を `mailto:` でメールアプリへ渡す方式
- 入力内容はページ内にもサーバーにも保存しない
- メールアプリが開かない場合に備え、内容コピー用の欄を追加

### 公開前に必ず変更すること

`index.html` 内の以下を、実際の受信用メールアドレスへ変更してください。

```js
const CONTACT_EMAIL = 'your-email@example.com';
```

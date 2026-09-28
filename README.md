# LifeLV — 製品LP

iPhone アプリ「LifeLV」（内部名 LifeLoop）の製品紹介ページ。GitHub Pages で公開する想定。

- 公開URL: https://shoheicraftdev-design.github.io/life-lv-lp/
- App Store: **公開中**（2026-09-10）。`https://apps.apple.com/jp/app/lifelv/id6809692228`
- サポート / プライバシーポリシー / 利用規約: https://shoheicraftdev-design.github.io/life-lv-support/

## 位置づけ

えも日LP（`emo-diary-lp`）・Sodato LP（`sodato-lp`）・GearDeban LP（`geardeban-lp`）・レコログLP（`recipe-log-lp`）・SwingTwin LP（`swingtwin-lp`）と同じく、
**匿名ライン（note・Xで製品名を出さない）を維持したままアプリ名とストアURLを出せるチャネル**。
サポート・法務ページは別リポジトリ `life-lv-support` が持つ（ここには置かない）。

★**ASC のマーケティングURLにこのURLを設定済み（ver-1.1・2026-09-17）。** iOS の app-ads.txt 認証（AdMob）はこの欄を起点にドメインを決める。
v1.0 は未設定のまま公開して認証が通らなかったため、ver-1.1 の掲載情報に同梱して入れた（台帳 `h-483zsj`）。公開中の lookup の `sellerUrl` がこの URL。

## 内容の版

**v1.0（2026-09-10 App Store 公開・build 2）に合わせて作成し、ver-1.1（2026-09-17 公開）でも内容は変わらない**（1.1 は不具合修正とマーケティングURLの設定のみ・2026-09-28 点検 `d-yso5qm`）。参照: `life-loop/docs/appstore/ver-1.1-submission.md`・`v1-store-listing.md`

## 素材

`images/` のスクリーンショットは、アプリ側リポジトリ `life-loop` の
`docs/appstore/screenshots/6.9-inch/`（提出用・1320×2868）を長辺640pxへ縮小したもの。
差し替える場合は元の 1320×2868 から作り直すこと。`appicon.png` は `assets/appicon-lifelv.png` の縮小（256px）。

| ファイル | 元 | 内容 |
| :--- | :--- | :--- |
| `shot-today.png` | `01-today.png` | 今日の画面（枠に並ぶタスクと「今日はやらない」「やった」） |
| `shot-progress.png` | `03-record.png` | 記録（現在のレベル・分野ごとのステータス・これまでの道のり） |
| `shot-levelup.png` | `02-levelup.png` | レベルアップ（称号と分野ごとの増分） |
| `shot-settings.png` | `05-settings.png` | 設定（1日の枠・朝のお知らせ・買い切り¥480） |

## 文言のルール（アプリ側 `docs/appstore/v1-store-listing.md` を継承）

- **本アプリはポートフォリオ初の広告つき・課金つき**。「広告が出ること」「買い切りで消せること」を
  掲載文と同じくLPにも明記する（後から知って低評価になるのを避ける）。無料側を「機能制限つき」と書かない
  ——制限しているのはカテゴリ数だけで、機能は無料でも全部使える。
- **「今日の枠はその日最初に開いたときに確定する」を隠さない。** 日中に登録したタスクが今日の枠に出ないのは
  設計であって不具合ではない（要件書 §3.2）。ここを書かないと「登録したのに出ない」の問い合わせになる。
- **称号は偏りから作られる＝名指しされる。** 掲載文の「真に受けないでください」を落とさない。
- **免責を落とさない**（規約第5条）。レベル・経験値・時間は入力の集計であり、活動量の計測や
  健康・生産性の指導・診断ではない。
- 他人との比較・順位・SNS共有の機能は無い。「もっとやりましょう」と急かさない（要件書 §2-3）。
- 表示名は **LifeLV**。リポジトリ・ターゲット・スキーム・バンドルIDは `LifeLoop` のままだが、
  利用者に見えるものではないのでLPには出さない。

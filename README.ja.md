<div align="center">

# XXD Panel 119｜手縫い布と余白の記録

少数の布片と針目に、写真の温かな記憶を託す。

<a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <strong>日本語</strong> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

## サンプル展示

本项目已发布 8 张实际样片，图片文件位于 `assets/examples/`。

| sample-05 | sample-06 |
| --- | --- |
| ![sample-05](assets/examples/sample-05.png) | ![sample-06](assets/examples/sample-06.png) |
| sample-07 | sample-08 |
| ![sample-07](assets/examples/sample-07.png) | ![sample-08](assets/examples/sample-08.png) |
| sample-09 | sample-10 |
| ![sample-09](assets/examples/sample-09.png) | ![sample-10](assets/examples/sample-10.png) |
| sample-11 | sample-12 |
| ![sample-11](assets/examples/sample-11.png) | ![sample-12](assets/examples/sample-12.png) |

## 向いている場面と解決する課題

印象的な人物、物、動作を残したいのに背景が混み合う写真を、**Panel 119** は手縫いのテキスタイル・コラージュへ凝縮します。少数の大きな布片、切りっぱなしのアップリケ、少量の刺繍で小さな焦点を作り、非常に大きな余白が繊維と針目を引き立てます。

### こんな場合に

- 人物、日常の物、旅の記憶の同一性を残し、温かい布の手触りを加えたい。
- 主体、輪郭、構造、姿勢、物語上の関係だけを抽出し、一つずつ描き写したくない。
- 生き生きと柔らかな2–4色の布と控えめな編集文を組み合わせたい。
- 上下、左右、デザインのみ、複数サイズ、4端末壁紙、フォルダ一括で出力したい。

### 解決すること

- 背景と無関係な細部の大半を取り除き、情報過多を防ぎます。
- 少数の大きな布片と手縫いの針目で識別性を作り、安っぽい手芸や定型コラージュを避けます。
- 比較画面を厳密な50:50の二領域だけにし、タイトル帯、下帯、第三領域を作りません。
- 毎回現在の原画像から一度で生成し、繰り返しのスタイル変換を避けます。

## 使い方のコツ

- **まず一枚の見やすい写真から始める：** 主体・動作・関係が分かる画像を選んでから、出力形式と比率を決めます。
- **パラメータを一文でつなぐ：** 「上下 / 左右 / デザインのみ + 16:9 / 3:4 / スマホ壁紙」のように指定し、PC・タブレット・スマートウォッチのサイズも追加できます。
- **残したい内容を明示する：** 人物、物、動作、関係、文字を指定し、レイアウトを細かく縛りすぎずスタイルに任せます。
- **文字の方法を選ぶ：** 画像から自動生成、`--text exact --copy` で逐字固定、または `--text none` で文字なしにできます。
- **写真領域とデザイン領域を伝える：** 上下・左右では写真を残す側と再設計する側を指定し、デザインのみ・壁紙では全画面を再設計すると伝えます。
- **一枚で試してから一括処理する：** モード、比率、文字、言語を一枚で確認し、同じ設定をフォルダに適用します。比較しやすいよう一度に一つだけ変更します。

## はじめに

```bash
git clone https://github.com/nevertoday/xxd-panel-119.git
npx skills add https://github.com/nevertoday/xxd-panel-119 --skill xxd-panel-119
```

インストール後に Agent セッションを再起動し、`$xxd-panel-119` を呼び出します。ユーザー単位の Codex には `--global --agent codex --yes` を追加できます。

```text
/xxd-panel-119 photo.jpg --mode top-bottom --size 3:4 --text prompt --locale ja-JP
/xxd-panel-119 photo.jpg --mode left-right --size 16:9 --text prompt --locale en-US
/xxd-panel-119 photo.jpg --mode design-only --size 9:16 --text none
```

完全な実行契約は [SKILL.md](SKILL.md)、実行アダプターは[英語](references/xxd-panel-119-prompt.en.md)／[中国語](references/xxd-panel-119-prompt.zh-CN.md)を参照してください。

## 原文プロンプト · 5言語

[简体中文](references/original-prompt/zh-CN.md) · [English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md)

中国語ファイルはユーザー原文を逐字保存し、実行時の唯一の創作・美的権威です。他の4言語は完全で忠実な閲覧用翻訳で、生成原文の代わりにはしません。

**特徴語：** 選択的な抽出 · 手縫いテキスタイル・コラージュ · 綿麻繊維 · 切りっぱなしアップリケ · 少量の刺繍 · 2–4色 · 非常に大きな余白 · 編集的タイポグラフィ

## クイック判定

| 気になること | Panel 119 の答え |
|---|---|
| 抽象化しても原画像が分かるか | 主体、姿勢、物語上の関係を少数の布形状に凝縮します。 |
| 布で画面が埋まらないか | 小さな焦点を置き、余白と布の縁と針目でリズムを作ります。 |
| 色が重苦しくならないか | 写真由来の温かな2–4色を適度に明るく純粋にし、灰色味を除きます。 |
| 出力方向を変えられるか | 4モードと複数サイズで、美学を変えずに交付構造だけを対応させます。 |

## 4つの出力モード

- `top-bottom`：全幅の上下2領域のみ。実写を上、デザインを下に置き、各50%。
- `left-right`：全高の左右2領域のみ。実写を左、デザインを右に置き、各50%。上下構成へ回転しません。
- `design-only`：全画面を Panel 119 のデザイン翻訳にし、写真は見えない参照にします。
- `wallpaper-pack`：スマートフォン、iPad、デスクトップ、時計を端末ごとに生成。`linked` または `independent` を選べます。

モードと比率は複数指定できます。`1:1`、`3:4`、`4:3`、`4:5`、`5:4`、`2:3`、`3:2`、`9:16`、`16:9`、`21:9`、`5:7`、`7:5`、正確なピクセルに対応します。文字はプロンプト生成、指定文の逐字使用、なしから選べます。フォルダ入力では各画像を分離して処理し、PNGを一つの新しいタスクフォルダへ置きます。

<!-- xxd-readme-ads:start -->
## XXD について

XXD は Xiaoxiaodong のブランド名略称です。本プロジェクトの作成・管理：[@xiaoxiaodong01](https://x.com/xiaoxiaodong01)。

## Xiaoxiaodong マルチプラットフォーム会員 · 年額 CNY 699

> **広告表示：** 以下のQRコード、会員および有料サービスのリンクはXXDの広告情報です。スキャンや購入は任意であり、オープンソースの利用には影響しません。

年額会員ひとつで、**Knowledge Planet＋XXD会員プロンプトライブラリ＋すべてのGeneral Skills会員**の3つを利用できます。別々に購入する必要はありません。

<!-- xxd-panel-command-system:start -->

### Skills の連携方法

| 区分 | 含まれるもの | 役割 |
|---|---|---|
| **General** | [`xxd-panel-all`](https://github.com/xiaoxiaodong-ai/xxd-panel-all) | 利用可能な番号付きSkillsを検出し、画像・テーマ・用途から推薦し、複数スタイルや一括タスクを整理します。 |
| **Soldier** | `xxd-panel-NNN` | 各番号が固有の原文プロンプトと美学に従い、Generalから割り当てられた具体的な作業を完成させます。 |

<!-- xxd-panel-command-system:end -->

### 会員の内容

1. **WeChatでの一対一AI学習・プロジェクト相談**
   下のQRコードからXiaoxiaodongのWeChatを追加し、AI学習、ツール、実際のプロジェクトについて一対一で相談できます。代表的な質問は会員向けコンテンツに整理されます。
2. **継続更新する会員プロンプトライブラリ**
   [XXD会員プロンプトライブラリ](https://vip.xiaoxiaodong.ai/)には現在約3.2万件のプロンプトがあり、10万件超を目標に継続して拡充します。
3. **すべてのGeneral Skillsと利用サポート**
   ひとつの会員で全General Skillsを利用でき、使い方に困ったときは案内やQ&Aを受けられます。
4. **必要性の高い要望を優先**
   会員から寄せられた頻度と必要性の高いプロンプトやSkillsは、優先して検討・開発します。

### 開設方法

- [会員サイトから自分で開設](https://vip.xiaoxiaodong.ai/)できます。
- または下のQRコードからXiaoxiaodongのWeChatを追加し、一対一で開設サポートを受けられます。

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="Xiaoxiaodongへの連絡" width="280"></a></p>
<!-- xxd-readme-ads:end -->

## ライセンス

本プロジェクト（Skill、プロンプト、スクリプト、文書、付属サンプル画像を含む）は **PolyForm Noncommercial License 1.0.0** の下で提供されます。完全な法的条文は [LICENSE](LICENSE)、公式ページは <https://polyformproject.org/licenses/noncommercial/1.0.0> を参照してください。

分かりやすく言うと：

- 個人は学習、研究、実験、テスト、趣味のプロジェクト、私的娯楽に使用できます。慈善団体、教育機関、公的研究・安全・保健機関、環境保護団体、政府機関も使用できます。
- **非商業目的**であれば、使用、複製、変更、派生物の作成、共有が可能です。共有時には本ライセンス（または上記リンク）と、作者が示したすべての `Required Notice:` 文を添付する必要があります。
- 商用製品・サービス、有料納品、アクセス権やライセンスの販売、商業利用につながることが予想される用途には使用できません。商用利用には著作権者から別途書面による許可を得てください。
- 本契約が付与するのは明記された著作権ライセンスと限定的な特許ライセンスだけです。商標、ブランド名、その他明記されていない権利は付与されず、ライセンスを第三者へ再許諾することもできません。
- 書面で違反通知を受けた場合、32 日以内に遵守状態へ戻り、実際の是正措置を取らなければライセンスは直ちに終了します。特許侵害を書面で主張した場合も特許ライセンスが終了します。
- 内容は法律が認める範囲で「現状のまま」提供され、保証はありません。利用に伴うリスクと損失は利用者が負います。

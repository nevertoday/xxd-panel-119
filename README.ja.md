<div align="center">

# XXD Panel 119｜手縫い布と余白の記録

少数の布片と針目に、写真の温かな記憶を託す。

<a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <strong>日本語</strong> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

## サンプル展示

以下のサンプルはそれぞれ異なる原画像を使い、Panel 119 が一枚ずつ独立した一回の生成で作成しました。AIメタデータは削除済みです。横長は左に実写、右にデザインを置く厳密な50:50、縦長は上に実写、下にデザインを置く厳密な50:50です。

サンプルの文案は各原画像に基づく英語で生成しています。

**16:9 横長 · 左右 50:50**

| sample-05 | sample-06 |
|---|---|
| ![sample-05](assets/examples/sample-05.png) | ![sample-06](assets/examples/sample-06.png) |
| ![sample-07](assets/examples/sample-07.png) | ![sample-08](assets/examples/sample-08.png) |

**3:4 縦長 · 上下 50:50**

| sample-09 | sample-10 |
|---|---|
| ![sample-09](assets/examples/sample-09.png) | ![sample-10](assets/examples/sample-10.png) |
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

## 写真を作品に変える流れ

主体と物語上の関係を特定 → 背景の大半を削除 → 少数の大きな布片と簡潔なシルエットで再構成 → 重なり、切りっぱなしの縁、少量の針目を加える → 焦点を小さくし大量の余白で構成 → 少数の言葉を静かに配置。

## 完成品の識別ポイント

- 写真の同一性、構造、姿勢、自然光と色調を残し、軽い調色だけを行います。環境は延長可能ですが主体は伸ばしません。
- 必要な情報だけを残し、全ての物や場面全体を描き写しません。
- 綿麻繊維、布目、不規則な裁断、わずかなずれ、切りっぱなしのアップリケと少量の刺繍が触感を作ります。
- 主体は偏心、端寄せ、浮遊、部分切り取りが可能で、非常に大きな余白が構図に参加します。
- 写真由来2–4色は鮮やかで柔らかく親しみやすく、濁り、古びた色、重苦しさを避けます。
- 主体、場所、動作、感情、比喩から生まれる少量の文字を余白や主体の縁に置き、字体や言語を固定しません。

## 4つの出力モード

- `top-bottom`：全幅の上下2領域のみ。実写を上、デザインを下に置き、各50%。
- `left-right`：全高の左右2領域のみ。実写を左、デザインを右に置き、各50%。上下構成へ回転しません。
- `design-only`：全画面を Panel 119 のデザイン翻訳にし、写真は見えない参照にします。
- `wallpaper-pack`：スマートフォン、iPad、デスクトップ、時計を端末ごとに生成。`linked` または `independent` を選べます。

モードと比率は複数指定できます。`1:1`、`3:4`、`4:3`、`4:5`、`5:4`、`2:3`、`3:2`、`9:16`、`16:9`、`21:9`、`5:7`、`7:5`、正確なピクセルに対応します。文字はプロンプト生成、指定文の逐字使用、なしから選べます。フォルダ入力では各画像を分離して処理し、PNGを一つの新しいタスクフォルダへ置きます。

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

<!-- xxd-readme-ads:start -->
## XXD について

XXD は Xiaoxiaodong のブランド名略称です。作成・管理： [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## サポートとメンバーシップ

> **広告表示：** このセクションのQRコードおよび有料会員・サービスのリンクはXXDのプロモーション情報です。スキャンや購入は任意であり、オープンソースの利用には影響しません。

### Xiaoxiaodong 総控 · 将軍総指揮 Skill · CNY 100

CNY 100 の一回払いで、このシリーズの将軍総指揮 Skill（`xxd-panel-all`）を利用できます。全兵士 Skills の統括、推薦、指名派遣、一括調整に対応します。WeChat では「将軍総指揮 Skill」と記載してください。

<!-- xxd-panel-command-system:start -->
**購入後に利用可能：全隊を指揮する「将軍 Skill」**

| 階級 | Skill | 担当 |
|---|---|---|
| **将軍級** | [`xxd-panel-all`](https://github.com/xiaoxiaodong-ai/xxd-panel-all) | 利用可能な番号付き Skills の検出、画像・テーマ・用途からの推薦、番号指定の派遣、同一素材の複数スタイル試作、フォルダー画像の一括割り当てと個別派遣。 |
| **兵士級** | `xxd-panel-NNN` | 各番号が固有の原文プロンプトと美学だけを実行し、将軍から渡された一つの仕事を完成させます。 |

将軍 Skill は、番号付き Skills 全隊の司令塔です。購入後すぐに利用でき、インストール、更新、編成、派遣方法についてサポートを受けられます。将軍は整理と派遣だけを担当し、兵士の原文美学を改変・混合・上書きしません。各完成作品は、選ばれた兵士 Skill が独立して制作します。
<!-- xxd-panel-command-system:end -->

### 知識星球＋会員プロンプトライブラリ＋全将軍 Skills 会員 · 年額 CNY 699

[知識星球](https://wx.zsxq.com/group/15554814142882)、[XXD 会員プロンプトライブラリ](https://vip.xiaoxiaodong.ai/)、全将軍 Skills 会員は同じ会員権です。**一度の年額決済で3つの特典をすべて利用でき、二重の購入は不要です。**

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

---

<div align="center">

## ☕ オープンソースを支援

このプロジェクトが役に立ったら、Buy Me a Coffee から任意で応援していただけます。

<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>

</div>
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

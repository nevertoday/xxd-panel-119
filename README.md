<div align="center">

# XXD Panel 119｜手缝布艺留白志

让少数布片与针迹，留下照片最温暖的记忆

<strong>简体中文</strong> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

## 样张展示

本项目已发布 8 张实际样片，图片文件位于 `assets/examples/`。

| sample-05 | sample-07 | sample-09 | sample-11 |
| --- | --- | --- | --- |
| ![sample-05](assets/examples/sample-05.png) | ![sample-06](assets/examples/sample-06.png) |
| sample-07 | sample-08 |
| ![sample-07](assets/examples/sample-07.png) | ![sample-08](assets/examples/sample-08.png) |
| sample-09 | sample-10 |
| ![sample-09](assets/examples/sample-09.png) | ![sample-10](assets/examples/sample-10.png) |
| sample-11 | sample-12 |
| ![sample-11](assets/examples/sample-11.png) | ![sample-12](assets/examples/sample-12.png) |

## 适用场景与解决的问题

当照片里的人、物或动作值得留下，但背景过于拥挤时，**Panel 119** 将核心形象提炼为手工缝制纺织拼贴。少数大布片、毛边贴布和少量刺绣组成小尺度视觉焦点，超大量留白让棉麻纤维与针迹有被看见的空间。

### 适合这些情况

- 为人物、日常物件和旅行记忆保留真实身份，同时增加温暖的布艺触感。
- 从复杂照片提炼主体、轮廓、结构、姿态和叙事关系，不逐物转绘原场景。
- 喜欢鲜活而柔软的 2–4 色布料配色与克制的编辑式文案。
- 需要同风格的上下、左右、纯设计、多比例、四端壁纸或目录批处理。

### 它替你解决什么

- 主动删掉大部分背景和无关细节，避免视觉信息堆积。
- 以少量大布片与手工针迹建立识别度，避免廉价手作感和模板化拼贴。
- 对照画布严格只有两个 50:50 区域，无标题带、底栏或第三分区。
- 每张从当前原图单轮生成，避免中间结果二次风格化。

## 原始提示词 · 五种语言

[简体中文](references/original-prompt/zh-CN.md) · [English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md)

中文文件逐字保留用户原文，是唯一运行时创作与审美权威。其他四种语言为完整忠实的阅读译文，不替代生图原文。

**关键词：** 选择性提炼 · 手工缝制纺织拼贴 · 棉麻纤维 · 毛边贴布 · 少量刺绣 · 2–4 色 · 超大量艺术留白 · 编辑式排版

## 快速判断：Panel 119 适合你吗？

| 你关心的问题 | 这套风格给你的回答 |
|---|---|
| 抽象后还能认出原图吗？ | 优先保留主体、姿态和叙事关系，以少量布片重新概括。 |
| 布艺会不会堆满画面？ | 主体被缩小为凝练焦点，留白与布边、针迹共同形成节奏。 |
| 颜色会不会沉闷？ | 从原图提取 2–4 种有温度的颜色，适度提亮提纯去灰。 |
| 能调整交付方向吗？ | 支持四种模式与多尺寸，只映射交付结构，不改审美。 |

## 它如何把照片变成成品

识别主体与叙事关系 → 删去大部分背景 → 以少量大布片和简洁剪影重构 → 加入层叠、毛边与少量针迹 → 缩小焦点并用大量留白构图 → 安静放入少量文字。

## 成品中最容易识别的特点

- 真实照片保留身份、结构、姿态、自然光影和色彩氛围，只轻微调色；可扩展环境，不拉伸主体。
- 设计只提炼最重要信息，不逐物描摹，不复制完整场景。
- 棉麻纤维、布纹、不规则剪裁、轻微错位、毛边贴布与少量刺绣形成真实触感。
- 主体可偏心、贴边、悬置或局部裁切，超大量留白主动参与构图。
- 2–4 种原图取色鲜活、柔软、亲切，避免灰脏、陈旧和沉闷。
- 文字很少，由主体、地点、动作、情绪或隐喻生发，安静落在留白或主体边缘；不固定字体或语种。

## 四种输出模式

- `top-bottom`：整张画布只有上下两个全宽区域，现实照片在上、设计在下，严格各占 50%。
- `left-right`：整张画布只有左右两个全高区域，现实照片在左、设计在右，严格各占 50%，不会旋转成上下结构。
- `design-only`：整张画布只呈现 Panel 119 的设计转译，照片只作为不可见参考。
- `wallpaper-pack`：按手机、iPad、桌面和手表分别生成完整设计壁纸，可选 `linked` 连贯套装或 `independent` 四张独立。

支持多选模式与比例（`1:1`、`3:4`、`4:3`、`4:5`、`5:4`、`2:3`、`3:2`、`9:16`、`16:9`、`21:9`、`5:7`、`7:5` 或准确像素），以及模型生成文字、准确文字和无文字。传入目录会递归扫描图片，每张源图独立处理，共用一次交付设置；最终 PNG 平铺放入一个新任务目录。

## 开始使用

```bash
git clone https://github.com/nevertoday/xxd-panel-119.git
npx skills add https://github.com/nevertoday/xxd-panel-119 --skill xxd-panel-119
```

安装后重新启动 Agent 会话，然后调用 `$xxd-panel-119`。也可以按需追加 `--global --agent codex --yes` 做用户级安装。

常用调用示例：

```text
/xxd-panel-119 photo.jpg --mode top-bottom --size 3:4 --text prompt --locale zh-CN
/xxd-panel-119 photo.jpg --mode left-right --size 16:9 --text prompt --locale en-US
/xxd-panel-119 photo.jpg --mode design-only --size 9:16 --text none
/xxd-panel-119 ./photos --mode design-only --size auto,3:4 --text prompt --locale ja-JP
```

完整运行契约见 [SKILL.md](SKILL.md)；运行适配器见 [英文](references/xxd-panel-119-prompt.en.md) 与 [中文](references/xxd-panel-119-prompt.zh-CN.md)。

<!-- xxd-readme-ads:start -->
## 关于 XXD

XXD 是小小东品牌名的缩写，本项目由小小东创建并维护： [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## 广告信息｜XXD 付费服务与会员

> **广告与商业信息声明：** 以下二维码、会员与付费服务链接属于小小东的广告信息。是否扫码或购买完全自愿，不影响本开源项目的访问与使用。


<!-- xxd-panel-command-system:start -->

将军 Skills 已包含在 699 元/年的统一会员权益中，无需单独购买。

| 层级 | Skill | 负责什么 |
|---|---|---|
| **将军级** | [`xxd-panel-all`](https://github.com/xiaoxiaodong-ai/xxd-panel-all) | 识别当前可用的编号 Skills；按图片、主题和用途推荐；按编号点将；组织同图多风格试稿；为图片文件夹批量分配并逐项派发。 |
| **士兵级** | `xxd-panel-NNN` | 每个编号只执行自己独立的原始提示词与审美，把将军派发的单个任务完成为成品。 |

<!-- xxd-panel-command-system:end -->

### 知识星球＋成员提示词库＋Skills 所有将军会员 · 699 元/年

[知识星球](https://wx.zsxq.com/group/15554814142882)、[小小东成员提示词库](https://vip.xiaoxiaodong.ai/)与 Skills 所有将军会员是同一份会员权益：**一次年费同时开通三项权益，无需重复付费。**

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>
<!-- xxd-readme-ads:end -->

## 许可证

本项目（包括 Skill、提示词、脚本、文档及随附样张）采用 **PolyForm Noncommercial License 1.0.0**。完整法律条文请见 [LICENSE](LICENSE)，官方页面见 <https://polyformproject.org/licenses/noncommercial/1.0.0>。

用人话说：

- 个人可以用于学习、研究、实验、测试、兴趣项目和私人娱乐；慈善机构、教育机构、公共研究/安全/卫生机构、环保组织及政府机构也可以使用。
- 在**非商业目的**下，你可以使用、复制、修改、制作衍生作品并分享；分享时必须同时提供本许可证（或上面的链接）以及作者提供的所有 `Required Notice:` 声明。
- 不允许用于商业产品或服务、收费交付、出售访问权或许可，或任何预期会带来商业应用的用途。需要商业使用时，请先向版权方另行取得书面许可。
- 本协议只授予其中明确写出的著作权许可和有限的专利许可，不授予商标、品牌名称或其他未明确授予的权利，也不能把你的许可再转授给他人。
- 如果收到书面违约通知，须在 32 天内纠正并采取实际补救措施，否则许可会立即终止；就专利侵权提出书面主张也会终止专利许可。
- 内容按“现状”提供，在法律允许的范围内不作任何担保，使用风险和可能的损失由使用者自行承担。

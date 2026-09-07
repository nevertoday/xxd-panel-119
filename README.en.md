<div align="center">

# XXD Panel 119｜Hand-Sewn Textile & Negative Space Chronicle

Let a few fabric pieces and stitches carry the photograph’s warmest memory.

<a href="README.md">简体中文</a> · <strong>English</strong> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

## Sample works

The samples below use different original references. Panel 119 generated each one independently in a single pass, and AI metadata has been removed. Landscape samples are strict 50:50 left–right pairs with reality on the left and design on the right; portrait samples are strict 50:50 top–bottom pairs with reality above and design below.

Sample copy is generated in English from each individual source.

**16:9 landscape · left–right 50:50**

| sample-05 | sample-06 |
|---|---|
| ![sample-05](assets/examples/sample-05.png) | ![sample-06](assets/examples/sample-06.png) |
| ![sample-07](assets/examples/sample-07.png) | ![sample-08](assets/examples/sample-08.png) |

**3:4 portrait · top–bottom 50:50**

| sample-09 | sample-10 |
|---|---|
| ![sample-09](assets/examples/sample-09.png) | ![sample-10](assets/examples/sample-10.png) |
| ![sample-11](assets/examples/sample-11.png) | ![sample-12](assets/examples/sample-12.png) |

## Best-fit situations and problems solved

When a photograph contains a memorable person, object or gesture but a crowded background, **Panel 119** distils the core image into a hand-sewn textile collage. A few large fabric pieces, raw-edge appliqué and sparse embroidery form a small focal point; exceptionally abundant negative space lets fibres and stitches be noticed.

### Best for

- Preserving identity in portraits, everyday objects and travel memories while adding warm textile tactility.
- Extracting subjects, contours, structures, poses and narrative relationships without redrawing the scene object by object.
- Combining 2–4 lively, soft fabric colours with restrained editorial copy.
- Delivering top-bottom, left-right, design-only, multiple sizes, four-device wallpapers or directory batches.

### What it solves

- Removes most background and irrelevant detail to prevent information overload.
- Builds recognition with few large fabric pieces and handmade stitches, avoiding cheap craft and template-like collage.
- Keeps comparison canvases to exactly two 50:50 regions without headers, footers or a third band.
- Generates each result directly from its current original in one pass, avoiding repeated stylisation.

## Original prompt · five languages

[简体中文](references/original-prompt/zh-CN.md) · [English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md)

The Chinese file preserves the user's wording verbatim and is the sole runtime creative and aesthetic authority. The other four languages are complete, faithful reading translations, not generation substitutes.

**Signature:** selective distillation · hand-sewn textile collage · cotton-linen fibres · raw-edge appliqué · sparse embroidery · 2–4 colours · exceptionally abundant negative space · editorial typography

## Quick fit check

| What you need to know | What Panel 119 gives you |
|---|---|
| Recognisable after abstraction? | The subject, pose and narrative relationships are prioritised and distilled into a few fabric shapes. |
| Will fabric fill the frame? | A small, refined focal point lets negative space, fabric edges and stitches establish rhythm. |
| Will colours feel dreary? | 2–4 warm source-derived colours are moderately brightened, purified and cleared of greyness. |
| Can delivery direction change? | Four modes and multiple sizes remap delivery structure without changing aesthetics. |

## Transformation logic

Identify subject and narrative relationships → remove most background → rebuild with a few large fabric pieces and simple silhouettes → add layering, raw edges and sparse stitches → reduce the focal point and compose with abundant negative space → quietly place a few words.

## Recognisable finished traits

- The photograph preserves identity, structure, pose, natural light and colour atmosphere with light grading only; extend surroundings without stretching the subject.
- The design retains only essential information, without tracing every object or copying the full scene.
- Cotton-linen fibres, fabric texture, irregular cutting, slight misalignment, raw-edge appliqué and sparse embroidery create real tactility.
- The subject may be off-centre, edge-adjacent, suspended or partly cropped; abundant negative space actively composes the image.
- 2–4 source-derived colours stay lively, soft and approachable rather than muddy, aged or dreary.
- Very little text grows from subject, place, action, emotion or metaphor and sits quietly in negative space or beside the subject; no fixed font or language.

## Four output modes

- `top-bottom`: exactly two full-width regions, reality above and design below, 50% each.
- `left-right`: exactly two full-height regions, reality left and design right, 50% each; it never rotates into a top-bottom layout.
- `design-only`: the full canvas contains only Panel 119's designed translation; the photograph remains a non-visible reference.
- `wallpaper-pack`: creates complete artworks for phone, iPad, desktop, and watch, either `linked` as a coherent family or `independent` as four separate works.

Modes and sizes may be combined. Supported sizes include `1:1`, `3:4`, `4:3`, `4:5`, `5:4`, `2:3`, `3:2`, `9:16`, `16:9`, `21:9`, `5:7`, `7:5`, and exact pixels. Text can be prompt-generated, user-exact, or absent. A directory is inventoried recursively and every source is isolated while sharing one set of delivery settings; final PNG files remain flat in one fresh task directory.

## Getting started

```bash
git clone https://github.com/nevertoday/xxd-panel-119.git
npx skills add https://github.com/nevertoday/xxd-panel-119 --skill xxd-panel-119
```

Restart the agent session after installation, then invoke `$xxd-panel-119`. Add `--global --agent codex --yes` when a user-level Codex installation is wanted.

Common examples:

```text
/xxd-panel-119 photo.jpg --mode top-bottom --size 3:4 --text prompt --locale en-US
/xxd-panel-119 photo.jpg --mode left-right --size 16:9 --text prompt --locale en-US
/xxd-panel-119 photo.jpg --mode design-only --size 9:16 --text none
/xxd-panel-119 ./photos --mode design-only --size auto,3:4 --text prompt --locale ja-JP
```

See [SKILL.md](SKILL.md) for the full runtime contract and the [English](references/xxd-panel-119-prompt.en.md) or [Chinese](references/xxd-panel-119-prompt.zh-CN.md) runtime adapter.

<!-- xxd-readme-ads:start -->
## About XXD

XXD is Xiaoxiaodong's abbreviated brand name. Created and maintained by [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## Support and membership

> **Advertising disclosure:** QR codes and paid membership/service links in this section are XXD promotional content. Scanning or purchasing is optional and does not affect access to this open-source project.

### Xiaoxiaodong Commander · General Command Skill · CNY 100

A one-time CNY 100 purchase unlocks this suite's General Command Skill (`xxd-panel-all`) for roster control, recommendations, Soldier dispatch, and batch coordination. Include “General Command Skill” in your WeChat message.

<!-- xxd-panel-command-system:start -->
**Your purchase unlocks the General Skill that commands the whole roster**

| Level | Skill | Responsibility |
|---|---|---|
| **General** | [`xxd-panel-all`](https://github.com/xiaoxiaodong-ai/xxd-panel-all) | Detect available numbered Skills; recommend by image, theme, or use; dispatch a chosen number; organize multi-style trials; and assign folders of images to individual jobs. |
| **Soldiers** | `xxd-panel-NNN` | Each numbered Skill executes only its own original brief and aesthetic, completing the individual job assigned by the General. |

The General Skill is the command center for the entire numbered-Skill roster. Your purchase unlocks it together with help for installation, updates, roster setup, and dispatch workflows. The General organizes and routes; it never rewrites, blends, or overrides a Soldier's original aesthetic. Every finished asset is still created independently by the selected Soldier Skill.
<!-- xxd-panel-command-system:end -->

### Knowledge Planet + Member Prompt Library + All General Skills Membership · CNY 699/year

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882), the [XXD Member Prompt Library](https://vip.xiaoxiaodong.ai/), and membership for all General Skills are one membership: **one annual payment unlocks all three benefits, with no second purchase required.**

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

---

<div align="center">

## Support this open-source project

If this project helps you, you’re welcome to support it through Buy Me a Coffee—entirely optional.

<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>

</div>
<!-- xxd-readme-ads:end -->

## License

This project—including the Skill, prompts, scripts, documentation, and accompanying sample images—is licensed under the **PolyForm Noncommercial License 1.0.0**. See [LICENSE](LICENSE) for the full legal text and <https://polyformproject.org/licenses/noncommercial/1.0.0> for the official page.

In plain language:

- Individuals may use it for study, research, experimentation, testing, hobby projects, and private entertainment. Charities, educational institutions, public research, safety or health organisations, environmental organisations, and government institutions may also use it.
- For **noncommercial purposes**, you may use, copy, modify, create derivative works, and share it. When sharing, you must also provide this license (or the link above) and every `Required Notice:` statement supplied by the author.
- It may not be used in commercial products or services, paid delivery, sale of access or licences, or any use expected to lead to commercial application. Obtain separate written permission from the copyright holder before commercial use.
- The agreement grants only the copyright licence and limited patent licence expressly stated. It grants no trademarks, brand names, or other unstated rights, and you may not sublicense your licence to others.
- After written notice of a violation, you must return to compliance and take practical remedial steps within 32 days, or the licences terminate immediately. A written patent-infringement claim also terminates the patent licence.
- The material is provided “as is”, without warranty to the extent permitted by law. Users bear the risks and potential losses arising from its use.

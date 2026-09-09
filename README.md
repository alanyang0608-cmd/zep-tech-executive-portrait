# Zep Tech Executive Portrait

An image-editing skill for polished, natural technology leadership portraits. Preserve the subject’s identity while improving lighting, grooming, clothing and composition.

## Visual style

- Neutral light-grey to near-white vertical gradient background.
- Slightly turned torso, upright head, relaxed gaze and restrained smile.
- Broad soft key light, gentle but visible facial shadows and subtle catchlights.
- Natural matte skin with fine detail; avoid oily highlights, artificial texture and waxy smoothing.
- Comfortable head-and-shoulder framing and refined, minimal clothing.

![Fictional portrait reference](references/finish-female-black.png)

## Use

Copy this repository’s contents into a skill directory named `zep-tech-executive-portrait` in your agent’s skills location, or ask your agent to install this repository as a skill. The entry point is [SKILL.md](SKILL.md). Instructions are currently written in Chinese.

Provide a subject photo and ask:

> Use $zep-tech-executive-portrait to create a refined studio portrait from this photo. Preserve my identity and use a restrained smile.

This skill requires an image-generation/editing tool. Its workflow targets the built-in imagegen capability; other runtimes may need tool integration adjustments. It does not include an image model or API credentials.

## References and privacy

All four bundled portrait examples are AI-generated fictional adults created without real-person image inputs. The fifth image is a person-free background standard. These references guide style only; the user’s supplied photo is the identity source. No original user photos, company-branded screenshots or personal source files are included.

See [visual guide](references/visual-guide.md) and [local skin-detail reconstruction](references/skin-detail-reconstruction.md). Identity fidelity and texture quality must be checked after each generation; outputs are not guaranteed to be identical across models.

## 中文说明

这是一套自然、精致的科技公司高管肖像技能：保留本人辨识度，统一灰白渐变背景、立体柔光、克制浅笑和自然哑光肤质。直接提供人物原照即可使用。参考图只提供风格，不作为人物身份来源。

## License

MIT — see [LICENSE](LICENSE). The license applies to the repository contents to the extent the author holds rights in them. Bundled reference images are AI-generated.

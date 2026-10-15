# jp-shibou-riyuusyo

**版本：v1.0**

面向中国留学生的日本大学学部志望理由书辅导 skill。支持查询学校官网资料、从零访谈起草、修改现稿、压缩字数和更换目标学校，默认以中文沟通、日语撰写正文。

## 安装

在 Codex 对话中输入以下内容：

```text
$skill-installer
请从 https://github.com/toukaihaku/jp-shibou-riyuusyo 安装此 skill。
SKILL.md 位于仓库根目录，安装名称为 jp-shibou-riyuusyo。
```

安装完成后，在下一轮对话中使用 `$jp-shibou-riyuusyo` 调用。

## 使用示例

```text
$jp-shibou-riyuusyo
我想申请2027年入学的○○大学○○学部○○学科，请从零开始辅导我。
```

也可以同时提供现有草稿，并说明需要修改、压缩的范围，或新的目标学校。

## 环境与可选搭配

完整流程需要 Codex 能够浏览学校官网，并运行代码统计正文字数。

`humanizer-jp` 为可选的日语润色 skill：已安装时会配合使用；未安装时，本 skill 会按内置规则完成润色。

详细工作流程见 [SKILL.md](SKILL.md)。


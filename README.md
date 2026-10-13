# 费曼学习法

把一个主题讲到能教给别人。先用给 12 岁孩子的类比解释，再标出容易混淆的地方，经过 2–3 轮追问和改写，用「讲给别人听」或「用到新场景」检验，最后留下一张教学笔记。

适合 Codex、Claude Code、Cursor、OpenCode 等支持 [Agent Skills](https://skills.sh/) 的工具。

## 安装

```bash
npx skills add LingJingMaster/feynman-learn
```

装到本机所有项目：

```bash
npx skills add LingJingMaster/feynman-learn -g -y
```

只装给 Codex：

```bash
npx skills add LingJingMaster/feynman-learn -g -a codex -y
```

先看仓库里有什么、不安装：

```bash
npx skills add LingJingMaster/feynman-learn --list
```

## 使用

在对话里说「用费曼学习法讲透……」，或显式调用 `$feynman-learn`。

它会先问两件事：想掌握的主题，以及当前水平（初学者 / 中级 / 高级）。已经说了的不会再问。

## 文件

- `SKILL.md`：技能说明
- `agents/openai.yaml`：界面名称与默认提示

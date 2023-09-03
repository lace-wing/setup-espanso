# setup-espanso

[English Version](README.md)

Lacewing 的 [Espanso](https://espanso.org) 配置。

## 使用方法
[Espanso](https://espanso.org) 允许你在任何地方插入文本片段。
当然了，它们是可自定义的，可配置的。
使用方法参见[其文档](https://espanso.org/docs/get-started/)。

此仓库包含 Lacewing 的 Espanso 配置。
你会看到一些常规文本片段，例如日期和时间。
不仅如此，还有一些**写作**，**游戏**，尤其是 **Terraria** 和 **tModLoader** 或单纯为了**好玩**的文本片段。
其中一些文本片段只有**简体中文**的版本。

要使用这些文本片段，你可以浏览配置文件中的 `trigger`，`triggers` 和 `regex` 或使用 Espanso 的搜索栏（<kbd>Alt</kbd>/<kbd>Opt</kbd> + <kbd>空格</kbd>）来了解它们。
如果你只想要其中的一部分，或者是略有不同的版本，你可以随意修改。
另外，别忘了阅读[文档](https://espanso.org/docs/get-started/)!

## 前置需求
- 安装好 [Espanso](https://espanso.org)
- 部分文本片段需要安装额外的 shell 指令，在此仓库中搜索 `ALERT` 查看具体信息

## 安装
1. 将此仓库克隆到 `~/.config/espanso/`
2. 确保 Espanso 的配置，`base.yml` 中导入了上述路径
   ```yml
   imports:
     - "~/.config/espanso/"
   ```
3. 看看有哪些文本片段然后开用！

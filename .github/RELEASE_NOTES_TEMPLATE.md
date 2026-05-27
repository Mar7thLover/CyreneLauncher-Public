<!--
Release body 模板。GitHub 在 Draft a new release 界面没有原生 release-template
机制，所以这只是一份**人类指南**——发布时手动复制下面的结构填进 Description 框。

启动器会把 Description（=release body）原样抓回并展示（去 Markdown 后做单行
intro，详情页保留原 Markdown）。所以尽量结构化，方便用户扫读。
-->

## 本次更新

- 简明 1-2 句话，描述这次补丁的主要变化（用户能直观感受到的）

## 适配的游戏版本

- **OS（国际服）**: 4.x.x（HoYoPlay）
- **CN（国服）**: 4.x.x（miHoYo Launcher）

## 已知问题

- 列出已知但本次没修的问题（如有）

## 详细变更

- 列变更项，每行一条，简洁
- 标注影响范围：`[hook]` `[RSA]` `[OS-only]` `[CN-only]` 之类

## 升级建议

- 是否必须升级（如游戏大版本更新 → 必须）
- 是否清旧 DLL（一般不必，启动器按 region 文件名分别存）

---

_由 Cyrene Launcher 拉取展示。Asset 文件名必须为 `Astrolabe_OS.dll` 和 `Astrolabe_CN.dll`，否则启动器无法识别。_

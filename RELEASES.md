# Releases / 版本记录

## Unreleased

### 0.2.4

- Admit the current Cordis 4.1 Host, align development packages with DSH 0.2.2-rc.1, and exercise tool results through the current native batch executor. Preserve the tool, prompt, streaming renderer, and interaction behavior.
- 允许当前 Cordis 4.1 宿主加载，开发依赖对齐 DSH 0.2.2-rc.1，通过当前原生批量执行器验证工具结果；保留工具、提示、流式渲染及交互行为。

### 0.2.3

- Resolve relative CSS imports as filesystem paths, preserving Windows drive letters and filenames. Use pnpm 11.28.5 instead of the unavailable 11.12.0 release when preparing Git dependencies.
- 相对 CSS 导入使用文件系统路径解析，保留 Windows 盘符与文件名。Git 依赖构建使用 pnpm 11.28.5，替换无法安装的 11.12.0。

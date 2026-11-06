# Releases / 版本记录

## Unreleased

### 0.2.5

- Admit the source-Web host's exact Cordis 4.0.6-alpha.2 peer while retaining the existing 4.1 range. Keep the tool and renderer unchanged; verify them against the declared current Core source.
- Explicitly require the fixed Git archive's prepare approval and installed Host/Client entry verification. A skipped build is not a usable installation.
- 补充接纳源码 Web 宿主的精确 Cordis 4.0.6-alpha.2 同级依赖，保留已有 4.1 范围。工具及渲染器行为不变，按声明的当前 Core 源码验收。
- 明确固定 Git 归档的 prepare 审批和安装后宿主、客户端入口验证；跳过构建不算安装可用。

### 0.2.4

- Admit the current Cordis 4.1 Host, align development packages with DSH 0.2.2-rc.1, and exercise tool results through the current native batch executor. Preserve the tool, prompt, streaming renderer, and interaction behavior.
- 允许当前 Cordis 4.1 宿主加载，开发依赖对齐 DSH 0.2.2-rc.1，通过当前原生批量执行器验证工具结果；保留工具、提示、流式渲染及交互行为。

### 0.2.3

- Resolve relative CSS imports as filesystem paths, preserving Windows drive letters and filenames. Use pnpm 11.28.5 instead of the unavailable 11.12.0 release when preparing Git dependencies.
- 相对 CSS 导入使用文件系统路径解析，保留 Windows 盘符与文件名。Git 依赖构建使用 pnpm 11.28.5，替换无法安装的 11.12.0。

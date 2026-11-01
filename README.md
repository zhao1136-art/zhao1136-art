<div align="center">

# 御天 / Yutian

**写安全工具的。东西都在这里，全部禁止商用。**

[![Focus](https://img.shields.io/badge/focus-Windows%20%E5%AE%89%E5%85%A8%20%C2%B7%20%E6%81%B6%E6%84%8F%E8%BD%AF%E4%BB%B6%E5%88%86%E6%9E%90%20%C2%B7%20%E5%86%85%E6%A0%B8-0078D6)](#-项目)
[![License](https://img.shields.io/badge/license-Noncommercial-EA6A00)](#-说明)

</div>

---

## 项目

### 安全

| 项目 | 说明 |
|---|---|
| [**antivirus-software**](https://github.com/zhao1136-art/antivirus-software) | 御天：Windows 安全防护套件。YARA 规则 + 9 个 ETW provider + C++ 原生层 + 沙箱 + 跨引擎确认 |
| [**tianti**](https://github.com/zhao1136-art/tianti) | 天体引擎：沙箱行为分析型检测引擎。capa 兼容规则 + 26 个危险行为检测器，不做特征码比对 |
| [**yutian-guardian-ai**](https://github.com/zhao1136-art/yutian-guardian-ai) | 二进制转灰度图 + 轻量 CNN + OOD 未知样本检测 |
| [**sys**](https://github.com/zhao1136-art/sys) | 御天内核驱动 `andun.sys`。12 个模块，用 GitHub Actions + WDK 云端编译 |

### 工具

| 项目 | 说明 |
|---|---|
| [**memory-optimizer**](https://github.com/zhao1136-art/memory-optimizer) | 纯 C 写的 Windows 内存分析工具（泄漏识别 / 碎片 / 热点 / PDF 报告） |
| [**SleepPostponeTool**](https://github.com/zhao1136-art/SleepPostponeTool) | 电脑休眠推迟工具，零依赖单文件 exe |
| [**wallpaper-maker-tool**](https://github.com/zhao1136-art/wallpaper-maker-tool) | 桌面壁纸制作与管理（Canvas 编辑器 + 1045 个 Emoji 素材） |
| [**poetry-duel-platform**](https://github.com/zhao1136-art/poetry-duel-platform) | AI 自动对诗平台：对联 / 接龙 / 唱和 / 飞花令 |

## 技术笔记

- **用 capa 规则做沙箱行为检测** —— 不靠特征码，只看程序跑起来做了什么。规则怎么写、分数怎么算、什么情况下会漏。
  → [tianti](https://github.com/zhao1136-art/tianti)
- **用 GitHub Actions 免费编译 Windows 内核驱动** —— 不装 WDK、不买证书，从 0 到一个能编出来的 `.sys`，含 16 个真实踩坑。
  → [sys](https://github.com/zhao1136-art/sys)

## 说明

- 所有项目采用 [PolyForm Noncommercial License 1.0.0](https://polyformproject.org/licenses/noncommercial/1.0.0)：**禁止商业使用**。
- 仓库内第三方组件（capa 规则、ClamAV、字体等）保留各自原有许可，以各处 README 的说明为准。
- 这些都是个人项目，按「现状」提供，不附带任何担保。

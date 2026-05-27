# IELTS English Learning System

## 使用方法

### 1. Obsidian（全平台笔记）

直接在 Obsidian 中打开 `E:\IELTS-read` 文件夹即可。

```
IELTS-read/
├── 01-每日精读/          ← 每天的精读笔记
├── 02-词汇库/            ← 生词、同义替换
├── 03-句式库/            ← 好句收藏 + 仿写 + 改写
├── 04-口语素材/          ← 口语话题卡
├── 05-写作练习/          ← 作文
├── 06-模考分析/          ← 错题分析
├── data/                ← Python 统计数据
├── main.py              ← CLI 工具
└── ielts.bat            ← Windows 快捷命令
```

iCloud 同步到 iPad/iPhone 即可全平台阅读。

### 2. Python CLI（PC 端学习辅助）

在 `E:\IELTS-read` 目录下打开终端（或 Cursor 终端）：

**Windows CMD：**
```
ielts start          → 创建今日精读模板
ielts plan           → 查看今日学习计划
ielts stats          → 学习统计
ielts vocab add ...  → 添加生词
ielts vocab review   → 间隔复习
ielts log 精读 90    → 记录学习时间
```

**Git Bash：**
```
python main.py start
python main.py plan
...
```

### 3. 今日开始学习

1. Obsidian 打开此文件夹
2. 终端运行 `ielts start` 或 `python main.py start`
3. 打开 `01-每日精读/2026-04-27.md` 开始精读

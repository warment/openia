# OpenIA

## English

OpenIA is a Codex-first lab for practical AI workflows, daily dev logs, and evidence-driven network diagnostics.

It exists for one reason: turn everyday engineering work into something repeatable, observable, and easy to continue the next day.

### What stands out

- `daily-dev-log-skill` turns Git activity and working tree state into a real daily log.
- Network diagnostics scripts collect route, latency, and ISP evidence in a repeatable format.
- The workspace keeps long-running project context in plain files instead of hiding it in chat history.
- The repo is built around beginner-friendly automation: small commands, clear output, and no mystery state.

### Public highlights

- Public skill repo: [daily-dev-log-skill](https://github.com/warment/daily-dev-log-skill)
- Daily worklog pipeline: incremental capture, compression, consolidation, and handoff notes
- ISP diagnostics: router-aware reports and route analysis for provider troubleshooting

### How it is organized

```mermaid
flowchart TD
    A["Git activity"] --> B["Daily dev log"]
    B --> C["now.md"]
    C --> D["today-YYYY-MM-DD.md"]
    D --> E["recent.md"]
    E --> F["archive.md"]
    A --> G["Network diagnostics"]
    G --> H["reports"]
    H --> I["evidence notes"]
```

### Why this repo exists

This project is a working notebook for real tasks, not a demo toy. It captures how to:

1. keep a daily record of progress without writing it by hand,
2. diagnose network problems with evidence instead of guesses,
3. build reusable Codex skills that can be shared with others.

## Русский

OpenIA — это практическая Codex-лаборатория для рабочих AI-процессов, дневника разработки и сетевой диагностики по доказательствам.

Здесь проект нужен для одного: сделать обычную инженерную работу повторяемой, наблюдаемой и удобной для продолжения на следующий день.

### Что здесь главное

- `daily-dev-log-skill` превращает действия в Git и состояние рабочей копии в настоящий дневник дня.
- Скрипты сетевой диагностики собирают маршрут, задержки и признаки проблем у провайдера в повторяемом формате.
- Контекст долгих задач хранится в обычных файлах, а не прячется только в истории чата.
- Проект построен так, чтобы было понятно начинающему: маленькие команды, ясный вывод, без скрытого состояния.

### Что уже есть публично

- Публичный навык: [daily-dev-log-skill](https://github.com/warment/daily-dev-log-skill)
- Дневник работы: инкрементальный сбор, сжатие, консолидация и заметка для передачи контекста
- Диагностика интернета: отчёты с учётом роутера и разбор маршрута до провайдера

### Как это устроено

```bash
git clone https://github.com/warment/openia.git
cd openia
```

### Зачем существует этот репозиторий

Это не демо-игрушка, а рабочий блокнот для реальных задач. Он показывает, как:

1. вести дневник прогресса без ручной записи,
2. диагностировать сеть по доказательствам, а не по ощущениям,
3. собирать повторно используемые навыки для Codex.

### Быстрый старт

```bash
git clone https://github.com/warment/openia.git
cd openia
```

Рабочая автоматизация лежит в отдельном публичном навыке:
[daily-dev-log-skill](https://github.com/warment/daily-dev-log-skill)

## 中文

OpenIA 是一个以 Codex 为中心的实践实验室，用来做 AI 工作流、每日开发日志和基于证据的网络诊断。

它只有一个目标：把日常工程工作变得可重复、可观察，并且更容易在第二天继续下去。

### 亮点

- `daily-dev-log-skill` 会把 Git 活动和工作区状态变成真实的每日日志。
- 网络诊断脚本会以可重复的格式收集路由、延迟和 ISP 证据。
- 项目上下文保存在普通文件里，不只依赖聊天历史。
- 整个仓库偏向新手友好：命令少、输出清楚、没有隐藏状态。

### 公开内容

- 公开技能仓库：[daily-dev-log-skill](https://github.com/warment/daily-dev-log-skill)
- 每日工作日志流程：增量收集、压缩、归档、交接说明
- ISP 诊断：带路由器信息的报告和路径分析

### 为什么存在这个仓库

这不是演示玩具，而是给真实任务用的工作笔记。它展示了如何：

1. 不靠手写也能保留每天的进度记录，
2. 用证据而不是感觉来诊断网络问题，
3. 把可复用的 Codex 技能沉淀下来并分享给别人。

### 快速开始

```bash
git clone https://github.com/warment/openia.git
cd openia
```

真正可运行的自动化在单独的公开技能仓库里：
[daily-dev-log-skill](https://github.com/warment/daily-dev-log-skill)

## Notes

This public repo is intentionally curated. It focuses on the showcase layer and avoids publishing local logs or machine-specific diagnostics.

# 📱 MiMo Social Scheduler

AI Social Media Scheduler powered by **Xiaomi MiMo**推理模型

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![MiMo](https://img.shields.io/badge/Powered%20by-MiMo-orange.svg)](https://github.com/XiaoMi/MiMo)

## 🏗️ Architecture

![Architecture](screenshots/01_arch.png)

## ✨ Features

- **12 Platforms**: WeChat, Weibo, Twitter, Instagram, LinkedIn, and more
- **MiMo Content Generation**: AI-powered post creation
- **Brand Voice**: Customizable tone and style
- **Smart Scheduling**: Optimal posting time analysis
- **Multi-Agent**: Content creator, scheduler, analytics
- **Engagement Tracking**: Real-time performance metrics

## 📊 Performance

| Metric | Value |
|--------|-------|
| Posts Published | 847 |
| Platforms | 12 |
| Engagement Rate | 89% |
| Follower Growth | 23K |
| Daily Token Usage | 3-5M tokens |

## 🚀 Quick Start

```bash
pip install mimo-social-scheduler
mimo-social create --content "Your brand message"
mimo-social schedule --platforms all --time "2026-05-26 10:00"
```

## 💻 Code

![Code Editor](screenshots/02_code.png)

## 🖥️ Terminal

![Terminal](screenshots/03_terminal.png)

## 📈 Dashboard

![Dashboard](screenshots/04_dashboard.png)

## 🔧 Tech Stack

- **AI Model**: Xiaomi MiMo-7B (long-chain reasoning)
- **Framework**: Python + Celery
- **Frontend**: React + TailwindCSS
- **Storage**: PostgreSQL + Redis
- **Deployment**: Docker + Kubernetes

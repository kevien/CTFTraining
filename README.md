# CTF Training

经典赛题复现平台

## 环境说明

题目环境采用 Docker 搭建

## 版权说明

项目内题目源码均从网络收集，如果侵权，请联系本人删除（ virink@outlook.com ）

## 贡献指南 Contribution Guide

### Repository Rules

#### Name Rules

比赛名称_年份_题目名称_其他 GameName_Year_ChallengeName_Others `/\w+_\d{4}_\w+/`

eg. `westerns_2018_shrine` and `ctf473831530_2018_web_virink`

#### Description Rules

Able to describe clearly what the challenge is.

**eg.**

- **护网杯 2018 WEB (4) easy_laravel**
- **CTF学习交流入群题 Web 20180626**

#### File Rules

- **Dockerfile (require)**
- **docker-compose.yml (require)**
- **README.md (require)**
- **SourceCode file or directory (require)**
- vhost.conf
- .gitignore
- LICENSE

Just like other challenge.

### How to contribute challenge

1. Create a challenge repository on GitHub
2. Create a new issue in this repository
3. Waiting for the audit
4. We will fork your repository after approval

### How to update existing challenge

1. Update your repository
2. Pull Request
3. Waiting for the audit
4. We will merge your repository after approval

# （AI 翻译） 自用，尝试翻译Grafana面板

# TeslaMate

[![CI](https://github.com/teslamate-org/teslamate/actions/workflows/devops.yml/badge.svg)](https://github.com/teslamate-org/teslamate/actions/workflows/devops.yml)
[![Publish Docker images](https://github.com/teslamate-org/teslamate/actions/workflows/buildx.yml/badge.svg)](https://github.com/teslamate-org/teslamate/actions/workflows/buildx.yml)
[![Coverage](https://coveralls.io/repos/github/teslamate-org/teslamate/badge.svg?branch=main)](https://coveralls.io/github/teslamate-org/teslamate?branch=main)
[![current version](https://img.shields.io/docker/v/teslamate/teslamate/latest)](https://hub.docker.com/r/teslamate/teslamate)
[![docker image size](https://img.shields.io/docker/image-size/teslamate/teslamate/latest)](https://hub.docker.com/r/teslamate/teslamate)
[![docker pulls](https://img.shields.io/docker/pulls/teslamate/teslamate?color=%23099cec)](https://hub.docker.com/r/teslamate/teslamate)

一款强大的自托管特斯拉数据记录工具 

- 采用**[Elixir](https://elixir-lang.org/)**语言编写
- 数据存储于**Postgres**数据库
- 通过**Grafana**实现可视化与数据分析
- 车辆数据发布至本地**MQTT**代理服务器

## 文档说明

完整文档请访问：[https://docs.teslamate.org](https://docs.teslamate.org/)

## 核心功能

### 基础功能

- 高精度行驶数据记录
- 零额外电量损耗：车辆可快速进入休眠状态
- 自动地址解析
- 轻松对接Home Assistant（通过MQTT协议）
- 无缝集成Node-Red与Telegram（通过MQTT协议）
- 地理围栏功能创建自定义区域
- 支持单个特斯拉账户管理多台车辆
- 充电成本统计
- 支持从TeslaFi和tesla-apiscraper导入数据

### 仪表板功能

点击下方链接查看预置仪表板的示例截图。

- [Battery Health](https://docs.teslamate.org/docs/screenshots/#battery-health)
- [Charge Level](https://docs.teslamate.org/docs/screenshots/#charge-level)
- [Charges (Energy added / used)](https://docs.teslamate.org/docs/screenshots#charges)
- [Charge Details](https://docs.teslamate.org/docs/screenshots#charge-details)
- [Charging Stats](https://docs.teslamate.org/docs/screenshots#charging-stats)
- [Database Information](https://docs.teslamate.org/docs/screenshots/#database-information)
- [Drive Stats](https://docs.teslamate.org/docs/screenshots#drive-stats)
- [Drives (Distance / Energy consumed (net))](https://docs.teslamate.org/docs/screenshots/#drives)
- [Drive Details](https://docs.teslamate.org/docs/screenshots/#drive-details)
- [Efficiency (Consumption (net / gross))](https://docs.teslamate.org/docs/screenshots#efficiency)
- [Locations (addresses)](https://docs.teslamate.org/docs/screenshots/#location-addresses)
- [Mileage](https://docs.teslamate.org/docs/screenshots/#mileage)
- [Overview](https://docs.teslamate.org/docs/screenshots/#overview)
- [Projected Range (battery degradation)](https://docs.teslamate.org/docs/screenshots#projected-range)
- [States (see when your car was online or asleep)](https://docs.teslamate.org/docs/screenshots#states)
- [Statistics](https://docs.teslamate.org/docs/screenshots/#statistics)
- [Timeline](https://docs.teslamate.org/docs/screenshots/#timeline)
- [Trip](https://docs.teslamate.org/docs/screenshots/#trip)
- [Updates (History of installed updates)](https://docs.teslamate.org/docs/screenshots#updates)
- [Vampire Drain](https://docs.teslamate.org/docs/screenshots#vampire-drain)
- [Visited (Lifetime driving map)](https://docs.teslamate.org/docs/screenshots/#visited-lifetime-driving-map)

## Screenshots

Sneak peak into TeslaMate interface and bundled dashboards. See [the docs](https://docs.teslamate.org/docs/screenshots) for additional screenshots.

![Web Interface](/website/static/screenshots/web_interface.png)

![Drive Details](/website/static/screenshots/drive.png)

![Battery Health](/website/static/screenshots/battery-health.png)

## Credits

- Initial Author: Adrian Kumpf
- List of Contributors:
- [![TeslaMate Contributors](https://contrib.rocks/image?repo=teslamate-org/teslamate)](https://github.com/teslamate-org/teslamate/graphs/contributors)
- Distributed under MIT License

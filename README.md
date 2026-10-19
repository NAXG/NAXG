# NAXG

漏洞挖掘与安全研究。做过红队攻防、溯源反制与漏洞专项检查，现在把 AI Agent 接进自动化漏洞发现和安全工具链。

## 方向

- **漏洞挖掘与利用**：以 Web/API 和代码审计为主，产出 POC/EXP 与复现靶场。
- **攻防对抗**：国家级、省级护网与攻防演练，承担外网打点、内网横向与域控夺取；蓝队侧做溯源反制与蜜罐诱捕。
- **工具开发**：Go / Python / C，资产测绘、分布式扫描平台、Agent 工具链
- **AI Agent**：Claude Code / Codex / PI，自研 Agent Harness

## 开源

| 项目 | 说明 |
| --- | --- |
| [cve_2019_0708_bluekeep_rce](https://github.com/NAXG/cve_2019_0708_bluekeep_rce) | CVE-2019-0708 BlueKeep RDP 远程代码执行利用 |
| [Cairn_X](https://github.com/NAXG/Cairn_X) | FGS 图驱动的通用状态空间搜索，首个落地场景为自主渗透测试 |
| [ThreatMCP](https://github.com/NAXG/ThreatMCP) | 微步在线威胁情报 MCP 服务器 |
| [ARL](https://github.com/NAXG/ARL) | ARL 资产侦察灯塔二开：升级 Python 3.12、修复扫描中断、稳定性增强 |
| [sangfor-af-api](https://github.com/NAXG/sangfor-af-api) | 深信服 AF 非官方 Python SDK，覆盖 1,235 个接口并自动生成文档 |
| [skills](https://github.com/NAXG/skills) | 基于 Semgrep / AST 的代码审计 Agent Skill |

## 自研平台（私有）

- **Argus / Argus-Scan / Argus-UI**：分布式资产扫描平台，插件化扫描链，多节点集群
- **SPArecon**：快速筛选高价值目标
- **RedGuard / stealthproxy**：内网对抗与隐蔽代理

## 联系

- 博客：https://naxg.github.io

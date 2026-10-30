### Hi, I'm V-T-V (@V-T-V) 👋

Current focus — **[Reins](https://github.com/V-T-V/reins)**: 自托管零信任远程运维平台 (self-hosted zero-trust remote operations).

- 单个 Go 二进制,被控端零入站端口(反向 WebSocket 穿 NAT)
- **Windows 远程操作一等公民**:PowerShell/服务管控/GUI 自动化/计划任务/截图
- mTLS + RBAC + 防篡改审计链;AI 代理规则门禁(`.reins/rules.md`)+ MCP Server
- MIT · [官网 60 秒 demo](https://v-t-v.github.io/reins/) · `scoop install reins` / `brew install V-T-V/reins/reins`

```bash
git clone https://github.com/V-T-V/reins && cd reins
echo "REINS_TOKEN=change-me" > .env && docker compose up -d
```

# verge-config

Clash Verge Rev 覆盖配置（已脱敏，无节点密钥，可安全同步）。

## 文件

- `groups-ai-auto.yaml`：仅保留 `AI自动选择`（url-test，美/日/新 17 节点）
- `rules-ai.yaml`：AI 域名直指 `AI自动选择`

## Windows 使用

1. 先在机场官网复制订阅链接，在 Verge 里添加订阅（不要把带 token 的链接进 git）
2. 在 Verge 的 分组/规则 里从 Raw URL 引用本仓库文件：
   - `https://raw.githubusercontent.com/QiuweiLiu/verge-config/main/groups-ai-auto.yaml`
   - `https://raw.githubusercontent.com/QiuweiLiu/verge-config/main/rules-ai.yaml`
3. 在订阅编辑里关联上述分组/规则，点更新即生效

## 安全

- 不要提交 `RhGl3dfLUv8k.yaml` / `profiles.yaml` / `clash-verge.yaml` / 任何带 `token=` 的链接

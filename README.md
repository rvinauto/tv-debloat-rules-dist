# tv-debloat-rules-dist

电视精简规则的**发布版**（自动生成，请勿手改）。供 CleanYourTV 电视精简助手在线下载。

- 索引：`https://cdn.jsdelivr.net/gh/rvinauto/tv-debloat-rules-dist@main/index.json`
- 备用：`https://raw.githubusercontent.com/rvinauto/tv-debloat-rules-dist/main/index.json`
- 推荐应用：`apps/index.json`（只收录官方发布页、已核对 SHA256 的 APK 链接；本仓库不存放 APK）
- 每个型号：`rules/<品牌>/<id>.json`。动作只有「停用」（`pm disable-user --user 0`），风险分 safe / caution；关键系统包已剔除，记录在各文件的 `rejected` 中。
- 规则经脚本自动审核（`review: auto-checked`），**不代表人工或真机验证**，使用风险自负。

来源与许可见 [NOTICE.md](NOTICE.md) 和 [LICENSE](LICENSE)。

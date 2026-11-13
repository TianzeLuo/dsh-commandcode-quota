# 变更日志

格式参考 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.1.0/)，版本号遵循[语义化版本](https://semver.org/lang/zh-CN/)。

## [0.1.2] - 2026-09-29

- 额度百分比统一保留一位小数，两位数以后的小幅变化也能看见。

## [0.1.1] - 2026-09-27

- 周 / 月额度与周期花费改用实时读数，不再与 5 小时窗口显示成两个数。
- 官方调整额度上限后，卡片会自动跟随新上限。

## [0.1.0] - 2026-09-27

- 会话头部新增 Command Code 额度按钮与卡片：5 小时 / 每周 / 月度窗口、重置倒计时、token、请求数与周期花费。
- 凭据与端点自动发现，界面文案跟随 DSH 的 locale。

[0.1.2]: https://github.com/TianzeLuo/dsh-commandcode-quota/compare/v0.1.1...v0.1.2
[0.1.1]: https://github.com/TianzeLuo/dsh-commandcode-quota/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/TianzeLuo/dsh-commandcode-quota/releases/tag/v0.1.0

# Offline Voice Control Smart Ball Light

⭐ 一款离线语音智能小球灯，兼容大部分小球（藤条）灯型号，为嘉立创智能训练营开源设计方案 ⭐

[![Latest Release](https://gitlab.soraharu.com/XiaoXi/Offline-Voice-Control-Smart-Ball-Light/-/badges/release.svg)](https://gitlab.soraharu.com/XiaoXi/Offline-Voice-Control-Smart-Ball-Light/-/releases)

🔗 [GitLab (Homepage)](https://gitlab.soraharu.com/XiaoXi/Offline-Voice-Control-Smart-Ball-Light) | 🔗 [OSHWHub](https://oshwhub.com/yanranxiaoxi/Offline-Voice-Control-Smart-Ball-Light) | 🔗 [GitHub](https://github.com/yanranxiaoxi/Offline-Voice-Control-Smart-Ball-Light)

## 🤔 这是什么

这是一款离线语音智能小球灯，使用 [嘉立创 EDA 专业版](https://pro.lceda.cn/) 进行开发。

本设计采用一块由 启英泰伦(ChipIntelli) 研发的 CI-C22GS02S 人工智能离线语音模块作为主控制器，其主控芯片型号为 CI1122。外壳采用公版 15cm 小球（藤条）灯，预计成本 7-10 元，可在各购物平台自行购买。

本设计分为两个版本。V1 版为基础双层板，可以使用离线语音控制 RGB 灯光，总配备了 8 颗 RGB 灯珠。V2 版为四层板，额外增加了底座定位孔，并支持红外输入、输出功能，总配备了 4 颗 RGB 灯珠、4 颗红外发射管、1 颗红外接收头（带解码）。

## 🛠️ 生产电路板

本项目的 Gerber 文件可以从 [Releases](https://gitlab.soraharu.com/XiaoXi/Offline-Voice-Control-Smart-Ball-Light/-/releases) 页面获取，并允许在开源许可范围内的商业目的使用。

*建议使用 [嘉立创](https://www.jlc.com/) 生产高品质电路板。

*It is recommended to use [JLCPCB](https://jlcpcb.com/) to produce high-quality circuit boards.

## ⚙️ 部署至嘉立创 EDA

1. 下载本项目 [工程文件](https://gitlab.soraharu.com/XiaoXi/Offline-Voice-Control-Smart-Ball-Light/-/releases) 到本地
2. 在嘉立创 EDA 专业版编辑器中选择 `文件` -> `导入` -> `嘉立创EDA(专业版)...`
3. 选择下载的工程文件压缩包（通常为 .zip 文件）并确认导入

## 📜 开源许可

基于 [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/) 许可进行开源。

本设计为嘉立创智能训练营开源设计方案。感谢嘉立创集团提供的终身免费电子设计自动化工具软件、智能训练营的培训资源、以及完全免费的电路板打样服务。

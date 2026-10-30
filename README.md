# 门店管家

Windows 单机进销存工具，使用 SQLite 本地账套。本仓库只发布程序包、校验文件和更新说明，不包含私有源码或经营数据。

[下载最新版本](https://github.com/wanglanaaa/Store-Manager-Releases/releases/latest)

## v2.2.0

[下载 Windows x64 程序包](https://github.com/wanglanaaa/Store-Manager-Releases/releases/download/v2.2.0/StoreManager-v2.2.0-win-x64.zip) · [SHA-256 校验文件](https://github.com/wanglanaaa/Store-Manager-Releases/releases/download/v2.2.0/StoreManager-v2.2.0-win-x64.zip.sha256) · [完整更新说明](https://github.com/wanglanaaa/Store-Manager-Releases/releases/tag/v2.2.0)

完整解压后运行 `StoreManager.WinForms.exe`，无需安装 Python 或 .NET。请勿只复制 exe；包内提供中文使用说明和文件校验清单。

Release 自动生成的 Source code 压缩包只包含本发布仓库的说明文件，请选择 Windows 程序包。更新前先备份账套，关闭软件，将新版解压到独立文件夹，再按对应版本说明打开原账套。

- 批次成本、默认先进先出与手选实际批次，可在同单任意顺序混用，成本和金额显示两位小数。
- 多份出库草稿可暂存、调用、修改及扫码，确认实销或赊销后才扣库存并登记账款。
- 入库扫码自动匹配已有商品，同条件的手动和扫码明细可累计数量并撤销；库存筛选和收银批次操作同步完善。
- 紧凑按钮、统一清空入口及清晰的蓝黑配色出库单。

首次打开兼容的旧管理账套时，先备份再升级为 v5。原正库存作为历史均价期初批次保留，不重算旧单据或反推原采购批次；回退旧程序需使用升级前备份。

草稿独立保存在账套旁的 `.sale-drafts.sqlite3` 文件，账套单文件备份不包含草稿。需要保留或移动时，关闭程序后将账套与对应草稿文件一起保留，不混用其他账套或不同备份时点的草稿。

程序包不含账套或经营数据；现场扫码枪、打印机及不同 DPI 的效果请结合实际设备核对。主窗口“检查更新”只查询版本、显示说明并打开下载页，不自动安装。

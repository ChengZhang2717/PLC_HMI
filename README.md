# Siemens-PLC-HMI

西门子 PLC 与 HMI 编程工作仓库。基于 TIA Portal 平台，集中管理 PLC 程序源码、HMI 画面、通用功能块库与项目文档。

## 目录结构

| 目录 | 内容 |
|---|---|
| `PLC_Sources/` | PLC 程序源码：SCL / LAD / FBD 导出文件，按项目或设备分文件夹 |
| `HMI_Screens/` | HMI 画面、脚本与模板导出 |
| `Libraries/` | 通用功能块（FB/FC）与可复用库 |
| `Docs/` | 操作说明、图纸、技术文档（PDF 等） |

## 约定

- **TIA 项目文件**：`.zap` 归档放入对应项目文件夹；编辑用的临时工程目录不入库
- **命名**：程序块使用 `FB_` / `FC_` 前缀 + 功能名，如 `FB_StepFurnace_TempCtrl`
- **版本记录**：每次提交在 commit message 中注明修改内容与对应设备/项目
- **分支**：`main` 为稳定版；改动较大时开分支，验证通过后合入

## 环境

- TIA Portal（版本以实际项目为准，在项目 README 中注明）
- WinCC / WinCC Unified

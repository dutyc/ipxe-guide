# iPXE Guide (开发中)

> **状态提示：本文档处于早期开发阶段 (WIP)**
>
> 本仓库是 [ipxe-netboot-stack-docker](https://github.com/dutyc/ipxe-netboot-stack-docker) 项目的配套文档。
> 由于主项目核心链路（iPXE -> iSCSI）尚未完全跑通，**本文档中的部分配置步骤、脚本参数及排错方案可能尚未最终验证或存在变动。**
>
> **请勿直接依据本文档进行生产环境部署。**
> 当前内容主要用于记录开发思路、测试过程及已知问题。欢迎 **Watch** 本项目，待主项目功能稳定后，我们将同步更新完整的正式教程。

##  文档目标

- 记录 iPXE + Docker + iSCSI 无盘启动的完整实现逻辑。
- 汇总开发过程中遇到的网络配置坑点与解决方案。
- 为主项目用户提供理论支撑和调试参考。

##  关联项目

- **主项目代码**: [ipxe-netboot-stack-docker](https://github.com/dutyc/ipxe-netboot-stack-docker)
- **官方参考**: [iPXE Documentation](https://ipxe.org)

##  贡献与反馈

如果您发现文档中有错误，或有更好的实践方案，欢迎提交 **Issue** 或 **Pull Request**。
*(注：投稿前请确认您的测试环境，并注明硬件/系统版本)*

## 📄 许可证

本项目采用 [MIT License](LICENSE) 开源。

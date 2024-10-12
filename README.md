# 最小可行治理 Minimum Viable Governance 

## 什么是最小可行治理？

最小可行治理（MVG）—— 尚处于Beta测试阶段 —— 是一种基于存储库的方法，用于在版本控制系统中运行的自由与开源项目中实施轻量级治理。它为一组自由与开源项目提供了一个整体的两级组织治理结构。在顶层（GitHub 上称为 “组织”）有一个技术指导委员会，负责对组织所有项目的总体方向和协调做出决策。在顶层之下是单个项目，采用轻量级、基于共识的治理方式。

共有两个目录：第一个是 org-docs，为技术指导委员会（TSC）提供最高级别的组织管理和政策；第二个是 project-docs，提供了单个项目管理的模板，但须遵守更大组织的政策和监督。

最小可行治理是一种快速建立合作关系的方法，可以随着组织和项目的发展而发展。如果你的组织发展壮大到有必要设立公司总部的地步，通常是在组织开始持有资金时，MVG 就是为了让这种过渡变得容易而设计的。

## 为什么要采用？

最小可行治理使您能够在一开始就对组织和子项目进行简单的治理，包括法律条款、许可和商标问题以及正当程序。及早实施这种管理有助于避免参与者之间的纠纷。

## 如何采用？

1. 复审文档并确定这是否适合你。
2. 在 [CHARTER.md](org-docs/CHARTER.md) 文件的第 1 部分中描述组织的使命。
3. 将 org-docs 存放在组织治理的仓库中，并让每位 TSC 初始成员在 [STEERING-COMMITTEE.md](org-docs/STEERING-COMMITTEE.md)文件上 “签名”，在文件中添加他们的姓名和组织隶属关系（如适用）。
4. 对于组织治理下的每个项目，在组织下面创建一个仓库，并让每个初始维护者在 [MAINTAINERS.md](project-docs/MAINTAINERS.md) 文件上 “签名”，在文件中添加他们的姓名和组织隶属关系（如适用）。
5. [选择一个许可证](https://choosealicense.com/) 或在每个项目的 MIT [LICENSE.md](project-docs/LICENSE.md) 文件中填写版权信息。
6. 开始工作吧。

## 参与贡献

嗨，你好！我们很高兴你愿意为这个项目做出贡献。你的帮助对于保持良好状态至关重要。

对本项目的贡献，将遵循[项目开源许可](LICENSE)公开[发布](https://help.github.com/articles/github-terms-of-service/#6-contributions-under-repository-license)。

请注意，本项目发布时附有[贡献者行为准则](https://raw.githubusercontent.com/EthicalSource/contributor_covenant/release/content/version/2/0/code_of_conduct.md) (CoC)，参与本项目即表示您同意遵守该条款；违反 CoC 的行为请报告至： opensource@github.com。为避免与 MVG 制品混淆，我们没有将 CoC 放在本仓库中。

### 提交 PR

1. [Fork](https://github.com/github/MVG/fork) 并 clone 本仓库
2. 创建一个新分支： `git checkout -b my-branch-name`
3. 实施变更
4. 推送到你 fork 的仓库并[发起一个 PR](https://github.com/github/MVG/compare)
5. 自我鼓励下，并等待你的 PR 接受评审与合并。

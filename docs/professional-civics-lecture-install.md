# 分专业思政课教学设计：下载与安装

版本：2.8.0。核对日期：2026-10-18（北京时间）。

| 平台 | 当前结果 | 下载或管理地址 | 安装方式 |
| --- | --- | --- | --- |
| GitHub | 已公开发布，完整14个技能文件 | [技能源码](https://github.com/artminding/SKILLS/tree/main/skills/professional-civics-lecture) · [单技能ZIP下载](https://raw.githubusercontent.com/artminding/SKILLS/main/downloads/professional-civics-lecture-2.8.0.zip) | 下载ZIP后导入支持Agent Skills的客户端；或使用下方命令 |
| SkillHub.cn | 已提交2.8.0，当前安全审核中；尚未取得公开下载链接 | [我的Skills（作者登录后查看）](https://skillhub.cn/dashboard) | 审核通过后打开技能详情，复制平台生成的安装指令；审核期间请使用GitHub ZIP |
| WorkBuddy | 已导入本人账户的个人技能库并启用；未完成公开市场上架 | [技能管理](https://www.workbuddy.cn/app/skills) | 专家·技能·连接器 → 技能 → 添加技能 → 上传技能 → 选择ZIP |

WorkBuddy个人库中的当前名称是 `professional-civics-lecture-2.8.0-20261017`，来源于上传文件名。个人库导入不会自动生成公开分享或下载地址。

## 从GitHub安装（支持Skills CLI的客户端）

需要安装Node.js/npm。以下命令会进入交互式安装流程；选择目标客户端和安装范围。

```bash
npx skills add artminding/SKILLS --skill professional-civics-lecture
```

此命令语法已依据Skills CLI官方资料核对，未在本机执行安装，以免重复改动现有技能。

## 克隆源码

```bash
git clone https://github.com/artminding/SKILLS.git
```

所需技能位于 `SKILLS/skills/professional-civics-lecture/`。后续技能继续放入仓库的 `skills/技能名称/` 下。

## Windows PowerShell：下载可导入的ZIP

在希望保存技能包的目录执行：

```powershell
Invoke-WebRequest -Uri 'https://raw.githubusercontent.com/artminding/SKILLS/main/downloads/professional-civics-lecture-2.8.0.zip' -OutFile '.\professional-civics-lecture-2.8.0.zip'
```

WorkBuddy优先使用界面导入此ZIP。没有核实到该平台官方的独立 `workbuddy install` 命令，不提供猜测命令。

## SkillHub CLI（审核通过后）

当前未获得本技能的公开安装标识，因此不提前给出可执行的安装命令。平台官方通用格式为 `skillhub install <技能标识> --dir <目标客户端skills目录>`；请以审核通过后技能详情页提供的实际标识为准。

## WorkBuddy公开上架的剩余步骤

[WorkBuddy开放平台](https://open.workbuddy.cn/)需要单独扫码登录及开发者入驻。当前登录页面提示登录即同意开发者服务协议、隐私保护指引和数据处理协议，需账户本人完成后才能继续提交公开上架。SkillHub实名认证不代表已完成WorkBuddy开放平台入驻。

## 官方操作参考

- [WorkBuddy技能安装与上传](https://www.codebuddy.cn/docs/workbuddy/From-Beginner-to-Expert-Guide/Function-Description/Skills-Market)
- [WorkBuddy开放平台入驻](https://open.workbuddy.cn/docs/onboarding)
- [SkillHub安装说明](https://skillhub.cn/install/skillhub.md)
- [Skills CLI](https://skills.sh/docs/cli)

问卷用于教学改进，匿名反馈与学习成效测验分开；具体功能与资料使用边界见技能正文。


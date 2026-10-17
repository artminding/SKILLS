# 分专业思政课教学设计：下载与安装

版本：2.8.0。核对日期：2026-10-18（北京时间）。

| 平台 | 当前结果 | 下载或管理地址 | 安装方式 |
| --- | --- | --- | --- |
| GitHub | 已公开发布，完整14个技能文件 | [技能源码](https://github.com/artminding/SKILLS/tree/main/skills/professional-civics-lecture) · [单技能ZIP下载](https://raw.githubusercontent.com/artminding/SKILLS/main/downloads/professional-civics-lecture-2.8.0.zip) | 下载ZIP后导入支持Agent Skills的客户端；或使用下方命令 |
| SkillHub.cn | 2.8.0已审核通过并正式发布 | [技能详情](https://skillhub.cn/skills/user_3e0f26a8/professional-civics-lecture) · [下载ZIP](https://api.skillhub.cn/api/v1/download?slug=%40user_3e0f26a8%2Fprofessional-civics-lecture) | 安装标识为 `@user_3e0f26a8/professional-civics-lecture`，见下方命令 |
| WorkBuddy | 个人库已导入并启用；公开上架已提交，审核中，平台提示预计7个工作日内出结果 | [个人技能管理](https://www.workbuddy.cn/app/skills) · [开发者审核列表](https://open.workbuddy.cn/skill/all) · [适配包ZIP](https://raw.githubusercontent.com/artminding/SKILLS/main/downloads/professional-civics-lecture-workbuddy-2.8.0.zip) | 审核期间可将适配包导入个人技能库；市场公开安装链接待审核通过后生成 |

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

## SkillHub CLI

需先按[官方安装说明](https://skillhub.cn/install/skillhub.md)安装SkillHub CLI。以下为官方命令格式与本技能公开标识组合的安装命令；尚未在本机执行，以免覆盖已安装版本。

```bash
# WorkBuddy（macOS/Linux常用路径）
skillhub install @user_3e0f26a8/professional-civics-lecture --dir ~/.workbuddy/skills
```

```powershell
# WorkBuddy（Windows PowerShell）
skillhub install '@user_3e0f26a8/professional-civics-lecture' --dir "$env:USERPROFILE\.workbuddy\skills"
```

也可将以下文字发给支持安装技能的AI：

> 请根据 https://skillhub.cn/install/skillhub.md ，安装 @user_3e0f26a8/professional-civics-lecture 。

## WorkBuddy发布记录与适配说明

已完成WorkBuddy开放平台提交，技能ID：`os_6c3bdd73a3498654`；版本：2.8.0；价格：免费；市场分类：教育学习；服务类目：教育服务 - 教育信息展示。最终资产列表显示“审核中”，平台提示预计7个工作日内出结果。

公开发布系统仅接受两级目录，因此WorkBuddy适配包将四份专业资料从 `references/programs/` 平移到 `references/`，同步修正引用，并补充平台要求的中英文简介、展示名、作者和版本字段。教学指令与资料内容不变，GitHub源码与SkillHub版本维持原目录结构。

## 官方操作参考

- [WorkBuddy技能安装与上传](https://www.codebuddy.cn/docs/workbuddy/From-Beginner-to-Expert-Guide/Function-Description/Skills-Market)
- [WorkBuddy开放平台入驻](https://open.workbuddy.cn/docs/onboarding)
- [SkillHub安装说明](https://skillhub.cn/install/skillhub.md)
- [Skills CLI](https://skills.sh/docs/cli)

问卷用于教学改进，匿名反馈与学习成效测验分开；具体功能与资料使用边界见技能正文。


# 沟通记录：安装 awesome-design-md

## 用户需求
- **时间**：2026-04-08
- **内容**：帮我安装这个文档：https://github.com/VoltAgent/awesome-design-md

## AI 理解与确认
用户希望在当前工作空间（项目 `25.skill`）中安装 `awesome-design-md` 文档库。该库是一个收集了诸多知名网站与平台 `DESIGN.md` 规范的仓库，用于指导 AI 代理生成 UI 界面。

## AI 执行过程
1. 在根目录下的 `提示词.txt` 中完整追加了用户的初始需求。
2. 使用 `git clone https://github.com/VoltAgent/awesome-design-md.git` 将远程仓库完整克隆到了本工作空间的 `awesome-design-md` 目录中。
3. 经查看，该库已成功拉取，包含 `design-md` 这个由各品牌（如 Apple、Figma、Claude 等）设计规范构成的文件夹。

## 待核对问题
目前整个代码库（58 个参考文档）已经就绪。需要进一步询问用户是否需要从中挑选某一个特定的品牌作为当前项目的主干设计规范（即将某个现成的 `DESIGN.md` 复制到项目根目录中进行开发）。

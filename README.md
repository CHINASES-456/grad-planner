# 研途规划 — 研究生三年规划追踪工具

## 使用地址

**https://chinases-456.github.io/grad-planner/**

手机和电脑都能打开。iPhone: Safari → 分享 → 添加到主屏幕。Android: Chrome → 菜单 → 添加到主屏幕。

## 功能

- 📅 **今日**：AI 根据你的目标 + 历史行为 + 对话内容生成每日计划，勾选完成
- 💬 **AI 对话**：随时跟 AI 导师交流，AI 了解你的完整数据，能做生活决策建议
- 📊 **看板**：时间分布饼图、自评趋势、三条路径（申博/考公/国企）投入趋势
- 📋 **任务库**：临时任务管理，逾期自动提醒
- ☁️ **云同步**：通过 GitHub Gist 在多设备间同步（设置 → 填入 GitHub Token → 上传/下载）
- 💾 **导出/导入**：JSON 格式，本地备份

## 云同步设置

1. 去 github.com → Settings → Developer settings → Personal access tokens → Tokens (classic)
2. 新建 Token，勾选 **gist** 权限，生成后复制
3. 在 app 设置页 → ☁️ 云同步 → 填入 Token → 保存 → 上传到云端
4. 另一台设备同样填入 Token → 从云端下载
5. 勾选"保存时自动同步"，之后每次保存自动上传

## 本地使用

双击 `index.html` 即可在浏览器中打开。数据保存在浏览器 localStorage 中。

# 研途规划 — 研究生三年规划追踪工具

## 使用方式

### 方式 1：本地使用（电脑）
双击 `index.html` 即可在浏览器中打开。数据保存在浏览器 localStorage 中。

### 方式 2：手机 + 电脑都能用（推荐）

将项目上传到 GitHub Pages（免费），获得一个网址，手机和电脑都能访问：

**第一步：创建 GitHub 仓库**
1. 去 [github.com](https://github.com) 注册/登录
2. 新建仓库（New Repository），名称如 `grad-planner`

**第二步：上传文件**（在仓库页面操作）
1. 点击 "uploading an existing file"
2. 把 `index.html` 拖进去
3. 提交（Commit changes）

**第三步：开启 GitHub Pages**
1. 仓库页面 → Settings → Pages
2. Source 选 "main" 分支，Save
3. 等 1 分钟，页面显示 `https://你的用户名.github.io/grad-planner/`
4. 在手机浏览器打开这个网址即可

**第四步：添加到手机主屏幕**
- iPhone：Safari 打开 → 底部分享按钮 → "添加到主屏幕"
- Android：Chrome 打开 → 菜单 → "添加到主屏幕"

### 跨设备同步
目前数据存储在各设备的浏览器中，互不影响。可以通过"设置 → 导出/导入 JSON"手动同步。

## 功能

- 🎯 目标设定：选择申博/考公/国企，自动生成 6 学期阶段目标
- 📝 每日记录：记录每天的活动、时长、目标匹配度、自评
- ✅ 任务清单：添加临时任务（如导师布置），设置截止日期，到期自动提醒
- 📊 仪表盘：时间分配饼图、自评趋势、阶段进度
- 🧠 AI 分析：调用 Claude API 做每周分析，给出导师级建议
- 💾 数据导出/导入

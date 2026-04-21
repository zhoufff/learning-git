# 🎓 Vibe Coding 系统学习路线 — 从零开始

> 不急着做项目，先把地基打好。每个模块都是独立的，按顺序来。

---

## 学习原则

1. **视频先行**：先看视频建立感性认识，不用记住所有细节
2. **动手跟练**：看完视频后跟着敲一遍代码
3. **不求精通**：每个模块达到"看懂+能改"就够了，不需要"从零手写"
4. **遇到不懂的就问 AI**：这本身就是 vibe coding 的核心技能

---

## 模块 0：互联网是怎么运作的（2小时）

> 在学任何具体技术之前，先搞懂"大图"。

### 学习目标
- 知道浏览器输入网址后发生了什么
- 知道"服务器"、"客户端"、"域名"是什么
- 知道网页是怎么从服务器到你屏幕上的

### 推荐视频
| 平台 | 搜索 | 说明 |
|:---|:---|:---|
| YouTube | `How the Internet Works in 5 Minutes` | 动画演示，5分钟看完 |
| YouTube | `Fireship "The Internet Explained"` | Fireship 频道，风格快节奏，很好懂 |
| B站 | `互联网是怎么运作的` | 中文讲解 |

### 关键概念
| 概念 | 一句话 |
|:---|:---|
| **浏览器** | 你用来看网页的软件（Chrome、Edge） |
| **服务器** | 存放网站文件的远程电脑，永远开着 |
| **域名** | `google.com` 这种人能看懂的网址 |
| **IP地址** | 服务器的真实"门牌号"，一串数字 |
| **DNS** | 域名→IP地址的"电话簿" |
| **HTTP** | 浏览器和服务器之间的对话规则 |
| **前端** | 在你的浏览器里运行的部分（你看到的） |
| **后端** | 在服务器上运行的部分（你看不到的） |

### ✅ 检验标准
能用自己的话说出来：输入 www.baidu.com 之后，屏幕上出现百度首页的这个过程中，经历了哪几步。

---

## 模块 1：HTML — 网页的骨架（3-5小时）

> 所有网页的基础，最简单也最重要。

### 学习目标
- 知道 HTML 是什么、长什么样
- 能看懂一个简单网页的结构
- 能自己动手改一个现成网页的内容

### 推荐视频
| 平台 | 搜索 | 时长 | 说明 |
|:---|:---|:---|:---|
| YouTube | `Traversy Media HTML Crash Course` | ~1小时 | 最经典的 HTML 入门，节奏好 |
| YouTube | `freeCodeCamp Learn HTML – Full Tutorial` | ~2小时 | 更详细，适合完全零基础 |
| B站 | `HTML 入门教程 速成` | 1-2小时 | 中文讲解 |

### 实战练习
1. 在电脑上新建一个 `test.html` 文件
2. 双击用浏览器打开
3. 尝试修改文字、添加图片、添加链接
4. 保存 → 刷新浏览器 → 看效果

### ✅ 检验标准
能自己写出一个包含标题、段落、图片、链接的简单页面。

---

## 模块 2：CSS — 网页的样式（5-8小时）

> HTML 决定"有什么"，CSS 决定"长什么样"。

### 学习目标
- 知道 CSS 怎么和 HTML 配合
- 看得懂颜色、间距、字体、布局的写法
- 能改网页的颜色、大小、位置

### 推荐视频
| 平台 | 搜索 | 时长 | 说明 |
|:---|:---|:---|:---|
| YouTube | `Traversy Media CSS Crash Course` | ~1小时 | 紧凑实用 |
| YouTube | `Web Dev Simplified "Learn CSS in 20 minutes"` | 20分钟 | 极速概览 |
| YouTube | `Traversy Media Flexbox Crash Course` | ~20分钟 | 现代布局必学 |
| B站 | `CSS 零基础入门` | 1-2小时 | 中文 |

### 重点掌握
| 内容 | 优先级 | 为什么 |
|:---|:---|:---|
| 颜色和文字 | ⭐⭐⭐ | 最常改的 |
| 盒模型（margin/padding/border） | ⭐⭐⭐ | 控制间距的核心 |
| Flexbox 弹性布局 | ⭐⭐⭐ | 现代网页布局的标准方式 |
| Grid 网格布局 | ⭐⭐ | 做卡片式排列 |
| 响应式（@media） | ⭐⭐ | 让手机也能正常看 |
| 动画（transition/animation） | ⭐ | 锦上添花 |

### 实战练习
做一个简单的"个人名片"网页：名字 + 职业 + 一段介绍 + 联系方式，纯手写不用 AI。

### ✅ 检验标准
能手动调整一个网页的颜色、字体、间距、布局，不需要问 AI。

---

## 模块 3：JavaScript — 网页的交互（5-8小时）

> HTML/CSS 是"静物画"，JavaScript 让网页"活起来"。

### 学习目标
- 知道 JS 能做什么
- 看懂变量、函数、条件判断、循环
- 理解"点击按钮→执行操作"的机制

### 推荐视频
| 平台 | 搜索 | 时长 | 说明 |
|:---|:---|:---|:---|
| YouTube | `Traversy Media JavaScript Crash Course` | ~1小时 | 快速概览 |
| YouTube | `freeCodeCamp Learn JavaScript – Full Course` | ~8小时 | 最全面，可以只看前3小时 |
| YouTube | `Fireship "JavaScript in 100 seconds"` | 100秒 | 先看这个建立大概念 |
| B站 | `JavaScript 零基础教程` | 2-4小时 | 中文 |

### 重点掌握
| 内容 | 优先级 | 为什么 |
|:---|:---|:---|
| 变量（let/const） | ⭐⭐⭐ | 存数据的基础 |
| 函数（function） | ⭐⭐⭐ | 所有逻辑的基本单元 |
| if/else 条件判断 | ⭐⭐⭐ | "如果…就…否则…" |
| 数组和对象 | ⭐⭐⭐ | 数据组织方式 |
| DOM 操作 | ⭐⭐ | JS 控制网页元素 |
| 事件监听（onclick等） | ⭐⭐ | 用户操作触发代码 |
| for 循环 | ⭐⭐ | 重复操作 |
| async/await | ⭐ | 后面学API调用时再看 |

### 实战练习
给模块 2 做的"个人名片"加一个暗色模式切换按钮（点一下换配色）。

### ✅ 检验标准
能看懂一段 JS 代码大概在做什么。不需要能从零写出来。

---

## 模块 4：Python 基础（8-12小时）

> 你的 xiaoshuo 和 juben 项目的语言。学了之后就不是看天书了。

### 学习目标
- 会运行 Python 文件
- 看得懂变量、函数、类、列表、字典
- 理解 import 导入和文件组织

### 推荐视频
| 平台 | 搜索 | 时长 | 说明 |
|:---|:---|:---|:---|
| B站 | `小甲鱼 零基础学 Python` | 系列课 | B站最经典 Python 教程，风格有趣（只看前30集就够） |
| YouTube | `freeCodeCamp Learn Python – Full Course` | ~5小时 | 英文最经典 |
| YouTube | `Fireship "Python in 100 seconds"` | 100秒 | 先看概览 |
| YouTube | `Traversy Media Python Crash Course` | ~1.5小时 | 快速入门 |

### 重点掌握
| 内容 | 优先级 | 为什么 |
|:---|:---|:---|
| 变量和数据类型 | ⭐⭐⭐ | 基础中的基础 |
| 函数 def | ⭐⭐⭐ | 组织代码的核心 |
| 列表 list / 字典 dict | ⭐⭐⭐ | Python 最常用的数据结构 |
| if/else/for/while | ⭐⭐⭐ | 逻辑控制 |
| 类 class | ⭐⭐ | 理解你项目里的 Agent 怎么组织的 |
| import 导入 | ⭐⭐ | 理解文件之间的关系 |
| 文件读写 | ⭐⭐ | JSON/文本文件操作 |
| pip 包管理 | ⭐ | 安装第三方库 |

### 实战练习
写一个Python脚本：读取一个文本文件，统计里面有多少个字，输出到屏幕上。全程靠自己，不用 AI。

### ✅ 检验标准
打开你 xiaoshuo 项目的任意一个 `.py` 文件，能看懂 60% 以上在干什么。

---

## 模块 5：数据格式和开发工具链（3-5小时）

> 把零散的知识穿起来。

### 5.1 数据格式

| 格式 | 长什么样 | 学习方式 |
|:---|:---|:---|
| **JSON** | `{"name": "张三", "age": 30}` | YouTube 搜 `JSON explained in 10 minutes` |
| **YAML** | `name: 张三` + 换行 + `age: 30` | YouTube 搜 `YAML tutorial for beginners` |
| **Markdown** | `# 标题` + `**加粗**` | 你的架构文档就是 Markdown，已经在用了 |

### 5.2 命令行 / 终端

| 平台 | 搜索 | 说明 |
|:---|:---|:---|
| B站 | `命令行 终端 基础教程` | 中文 |
| YouTube | `Command Line Crash Course` | 英文 |

你需要了解的：
- 怎么打开终端（你已经会了）
- `cd` 进入文件夹
- `python xxx.py` 运行脚本
- `pip install xxx` 安装库
- `git` 命令（你已经学了 ✅）

### 5.3 VS Code / Trae / Cursor

| 平台 | 搜索 | 说明 |
|:---|:---|:---|
| YouTube | `VS Code tutorial for beginners 2025` | VS Code 是所有 AI 编辑器的基础 |
| B站 | `Cursor AI 编辑器教程` | Cursor 专项 |

---

## 模块 6：Prompt 工程 — Vibe Coding 的核心技能（持续学习）

> 前面5个模块让你"看得懂"，这个模块让你"指挥得好"。

### 学习目标
- 知道怎么给 AI 写出高质量的指令
- 知道什么是 system prompt 和 cursor rules
- 学会"先让 AI 出方案→审方案→再执行"的工作流

### 推荐视频
| 平台 | 搜索 | 说明 |
|:---|:---|:---|
| YouTube | `McKay Wrigley cursor workflow` | Cursor 实操最好的频道 |
| YouTube | `Greg Isenberg vibe coding` | 产品 + AI 视角 |
| B站 | `Cursor AI prompt 技巧` | 中文实操 |

### 推荐资源
| 资源 | 链接 | 用途 |
|:---|:---|:---|
| cursor.directory | https://cursor.directory | 各种项目的 Cursor Rules 模板 |
| awesome-cursorrules | https://github.com/PatrickJS/awesome-cursorrules | GitHub 上最全的规则文件集合 |
| awesome-vibe-coding | https://github.com/bluegalaxy111/awesome-vibe-coding | 工具/资源大全 |

### 核心技巧（看完视频后实践）

**1. 分步给需求，不要一次甩一大段**
```
❌ "帮我做一个建筑作品集网站，要有首页、项目列表、关于我、联系方式，
    深色风格，响应式，要有动画效果"

✅ 第一步："先帮我搭建项目结构，列出需要哪些页面和组件"
   第二步："现在做首页的大 Banner 区域，深色背景"
   第三步："加上项目列表卡片区域，使用 Grid 布局"
```

**2. 先出方案再执行**
```
✅ "不要直接写代码。先分析一下这个需求，
    给我一个分步实施计划，列出每一步要做什么。"
    → 审完方案后 → "按这个计划执行第一步"
```

**3. 设置项目规则**
在项目根目录创建规则文件，让 AI 始终遵守你的偏好。

---

## 模块 7：实战项目（把前面学的串起来）

学完前 6 个模块后，做 1-2 个项目来串联知识：

### 项目 A：纯手写一个简单网页（不用AI）
- 目的：验证 HTML/CSS/JS 基础
- 内容：做一个单页的个人介绍或作品集
- 要求：纯手写，不用任何 AI，遇到不会的查文档

### 项目 B：用 AI 做一个有交互的网页（Vibe Coding方式）
- 目的：练习 Prompt 工程 + 审核 AI 输出
- 内容：比项目 A 更复杂，比如加上暗色模式、数据筛选、动画效果
- 要求：用 Cursor/Trae 的 AI 功能，但你要能**看懂**AI写了什么、**判断**写得好不好

---

## 学习节奏建议

每天 1-2 小时，不用赶：

```
第 1 周    模块 0 + 模块 1 （互联网 + HTML）
第 2 周    模块 2           （CSS）
第 3 周    模块 3           （JavaScript）
第 4-5 周  模块 4           （Python）
第 6 周    模块 5           （数据格式 + 工具链）
第 7 周起  模块 6 + 模块 7  （Prompt工程 + 实战项目）
```

> [!TIP]
> 模块之间不是硬隔离的。如果学 CSS 的时候想先跳去看 Python 也完全可以。重要的是每个模块都要**动手练**，光看视频没用。

---

## 互动学习平台（免费）

除了视频之外，这些平台可以在浏览器里交互式学习：

| 平台 | 链接 | 特点 |
|:---|:---|:---|
| **freeCodeCamp** | https://www.freecodecamp.org | 最推荐，交互式练习 + 免费证书 |
| **The Odin Project** | https://www.theodinproject.com | 完整免费课程，项目驱动 |
| **Scrimba** | https://scrimba.com | 可以在视频里直接改代码 |
| **W3Schools** | https://www.w3schools.com | 速查手册，边看边试 |

---

## GitHub 资源清单

| 仓库 | 用途 | 什么时候看 |
|:---|:---|:---|
| [awesome-vibe-coding](https://github.com/bluegalaxy111/awesome-vibe-coding) | 500+ 工具/资源大全 | 随时翻翻 |
| [awesome-cursorrules](https://github.com/PatrickJS/awesome-cursorrules) | Cursor 规则文件 | 模块 6 |
| [cursor-rule-framework](https://github.com/fbrbovic/cursor-rule-framework) | 项目管理工作流 | 模块 6 |
| [vibe-coding-ai-rules](https://github.com/obviousworks/vibe-coding-ai-rules) | AI 编程最佳实践 | 模块 6 |
| [Vibe-Coding-with-Cursor](https://github.com/pr0mila/Vibe-Coding-with-Cursor-A-Complete-Guide) | 完整教程 | 模块 6 |
| [freeCodeCamp](https://github.com/freeCodeCamp/freeCodeCamp) | 学习平台源码 | 不需要看 |

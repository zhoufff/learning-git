# 🎓 Vibe Coding 系统学习路线 — 从零开始

> 不急着做项目，先把地基打好。每个模块都是独立的，按顺序来。

---

## 学习原则

> 你是建筑师，不是泥瓦工。你不需要会砌墙，但你需要看得懂施工图、知道材料规范、发现现场跟图纸不符时能指出来。

1. **目标是"看懂"，不是"会写"**：你的实际工作流是 AI 写代码、你验收结果。所以每个模块的目标是看得懂 AI 写了什么、能判断好不好、能提出修改意见
2. **视频先行**：先看视频建立感性认识，不用记住所有细节
3. **AI 辅助练习**：学完概念后，让 AI 写一段代码 → 你试着理解每一行 → 不懂的问 AI 解释 → 提出修改意见看效果
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
| YouTube | `freeCodeCamp Learn HTML - Full Tutorial` | ~2小时 | 更详细，适合完全零基础 |
| B站 | `HTML 入门教程 速成` | 1-2小时 | 中文讲解 |

### 实战练习
1. 让 AI 帮你生成一个简单的个人介绍页面
2. 逐行阅读 AI 写的 HTML，尝试理解每个标签是干什么的
3. 自己动手改几个地方：换标题文字、改图片链接、加一段新内容
4. 保存 → 刷新浏览器 → 看效果是否符合预期

### ✅ 检验标准
看一段 HTML 代码，能指出哪里是标题、哪里是段落、哪里是图片、哪里是链接。能自己动手改内容。

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
1. 让 AI 生成一个"个人名片"网页（名字 + 职业 + 介绍 + 联系方式）
2. 阅读 CSS 部分，理解每条样式在控制什么
3. 自己动手改：换个背景色、调大字号、改间距，观察效果
4. 给 AI 提修改意见："把布局从纵向改成横向""加一个圆角卡片效果"，看 AI 改了哪里

### ✅ 检验标准
AI 写完 CSS 后，你能看懂它在控制什么，能自己微调颜色、间距这些简单属性。

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
| YouTube | `freeCodeCamp Learn JavaScript - Full Course` | ~8小时 | 最全面，可以只看前3小时 |
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
1. 让 AI 给你的"个人名片"加一个暗色模式切换按钮
2. 阅读 AI 写的 JS 代码，找出：哪里定义了函数、哪里监听了点击事件、哪里修改了页面样式
3. 试着让 AI 解释每一行在干什么
4. 自己改一个小细节：比如把按钮文字从"切换暗色"改成"🌙/☀️"图标

### ✅ 检验标准
AI 写完 JS 后，你能看懂代码大概在做什么，能指出"这个函数是处理按钮点击的"这种级别。

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
| YouTube | `freeCodeCamp Learn Python - Full Course` | ~5小时 | 英文最经典 |
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
1. 让 AI 写一个Python脚本：读取一个文本文件，统计字数并输出
2. 逐行阅读，找出：哪里打开了文件、哪里做了计算、哪里输出了结果
3. 让 AI 解释你看不懂的部分
4. 自己改需求："再加上统计行数""把结果保存到新文件里"，看 AI 怎么改

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

### 项目 A：用 AI 做一个网页，全程你来"验收"
- 目的：练习"看懂 AI 代码 + 判断质量 + 提修改意见"的完整流程
- 内容：做一个单页的个人介绍或作品集
- 要求：AI 每写完一部分，你先读懂再让它继续。遇到看不懂的问它解释。遇到不满意的用具体语言描述怎么改

### 项目 B：用 AI 做一个更复杂的网页
- 目的：练习 Prompt 工程 + 分步指挥 + 审核 AI 输出
- 内容：比项目 A 更复杂，比如加上暗色模式、数据筛选、动画效果
- 要求：用"先出方案→审方案→分步执行"的工作流。每一步都要能说出 AI 写了什么、为什么这么写

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
> 模块之间不是硬隔离的。如果学 CSS 的时候想先跳去看 Python 也完全可以。重要的是每个模块都要**让 AI 写代码给你读**，光看视频没用，但也不需要自己从零手写。

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

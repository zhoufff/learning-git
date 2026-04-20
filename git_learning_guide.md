# 🎓 Git 完整速查手册 —— 面向 Vibe Coding

> 建筑师版：所有概念都用你能理解的比喻来解释

---

## 一、核心概念

| Git 概念 | 建筑类比 | 说明 |
|---------|---------|------|
| **仓库（Repository）** | 一个项目的文件柜 | 存放所有代码和历史记录的地方 |
| **commit（提交）** | 给图纸盖个章、存个档 | 代码在某一刻的快照，附带备注 |
| **暂存区（Stage）** | 桌上摊开准备盖章的图纸 | 选好的、准备提交的文件 |
| **分支（Branch）** | 平行方案 | A方案和B方案可以同时存在，互不干扰 |
| **远程仓库（Remote）** | 云端档案室（GitHub） | 代码的网络备份，可多人访问 |
| **clone（克隆）** | 从档案室复印一整套图纸回来 | 把 GitHub 上的项目下载到本地 |
| **pull（拉取）** | 去档案室取最新版 | 从 GitHub 下载别人的更新 |
| **push（推送）** | 把改好的图纸送回档案室 | 把本地提交上传到 GitHub |
| **merge（合并）** | 把 A 方案和 B 方案合成最终版 | 把两个分支的代码合在一起 |
| **conflict（冲突）** | 两个人改了同一张图的同一个地方 | 需要手动决定保留谁的修改 |
| **.gitignore** | "这些文件不用归档"的清单 | 告诉 Git 忽略哪些文件 |

---

## 二、命令分级

### ⭐ 必须会（日常 90% 的操作）

#### `git status` — 查看当前状态
```bash
git status
```
**什么时候用：** 随时。不知道现在代码什么情况就敲一下，相当于看看桌上有哪些文件还没整理。

---

#### `git add .` — 选中所有修改的文件
```bash
git add .          # 加入所有修改
git add index.html # 只加入某个文件
```
**什么时候用：** 写完代码后，准备存档前。`.` 表示"全选"。

---

#### `git commit -m "备注"` — 存档
```bash
git commit -m "完成了首页布局"
```
**什么时候用：** 每完成一个小功能或修复一个 bug。备注写你干了什么，将来回头看能看懂。

> [!TIP]
> 好的备注示例：`"修复了登录按钮不跳转的问题"`
> 差的备注示例：`"改了点东西"` `"update"` `"asdf"`

---

#### `git push` — 上传到 GitHub
```bash
git push
```
**什么时候用：** commit 之后，想把代码备份到 GitHub 上。

---

### ⭐⭐ 需要了解（迟早用到）

#### `git pull` — 从 GitHub 拉取最新代码
```bash
git pull
```
**什么时候用：** 换了电脑、或 GitHub 上的代码被别人（或另一个 AI）改过了，需要同步。

---

#### `git clone` — 把 GitHub 项目下载到本地
```bash
git clone https://github.com/用户名/项目名.git
```
**什么时候用：** 新电脑上第一次获取项目，或者下载别人的开源项目。和 `git init` 的区别是——`init` 是从零创建，`clone` 是下载现有的。

---

#### `git log --oneline` — 查看提交历史
```bash
git log --oneline
```
**什么时候用：** 想看之前存了哪些档，每条显示一行。

输出长这样：
```
ff94397 添加 .gitignore 文件
8a0ba74 第一次提交：添加 README 文件
```

---

#### `git diff` — 查看文件改了哪里
```bash
git diff              # 查看还没 add 的修改
git diff --staged     # 查看已经 add 但没 commit 的修改
```
**什么时候用：** commit 之前想确认一下到底改了什么。

---

### ⭐⭐⭐ 了解概念即可（Agent Teams / 团队协作才用到）

#### `git branch` — 分支管理
```bash
git branch            # 查看所有分支
git branch 新分支名    # 创建新分支
git checkout 分支名    # 切换到某个分支
git checkout -b 新分支 # 创建并切换（常用）
```
**什么时候用：** 想在不影响主线的情况下试新功能。Agent Teams 中不同 AI 可能在不同分支工作。

---

#### `git merge` — 合并分支
```bash
git checkout master   # 先切回主线
git merge 分支名       # 把分支合并进来
```
**什么时候用：** 分支上的功能写完了，要合回主线。在 GitHub 上通常通过 "Pull Request" 界面点按钮完成。

---

#### `git stash` — 临时保存未提交的修改
```bash
git stash        # 把当前改动临时藏起来
git stash pop    # 把藏起来的改动恢复
```
**什么时候用：** 代码改到一半，突然要切分支处理别的事，又不想 commit 半成品。

---

### 🆘 救命命令（出问题时用）

#### 撤销还没 add 的修改
```bash
git checkout .               # 撤销所有修改，恢复到上次 commit 的状态
git checkout -- 文件名        # 只撤销某个文件
```
**什么时候用：** AI 帮你改完代码后发现全改崩了，想回到上一个正常版本。

---

#### 撤销已经 add 但没 commit 的文件
```bash
git reset HEAD .             # 取消暂存，文件修改还在
```
**什么时候用：** 不小心 `git add .` 了，想反悔。

---

#### 回退到之前的某个 commit
```bash
git log --oneline            # 先查看历史，找到想回去的版本号
git reset --hard 版本号       # 回退（⚠️ 会丢失之后的所有修改！）
```
**什么时候用：** 项目彻底搞砸了，想回到之前某个正常的状态。**慎用！**

> [!CAUTION]
> `git reset --hard` 会删除所有未提交的修改，不可恢复。用之前一定确认好。

---

## 三、日常工作流程图

```
AI 帮你写完代码
      ↓
  git add .          选中修改
      ↓
  git commit -m "xx" 存档
      ↓
  git push           上传 GitHub
      ↓
  继续写下一个功能…
```

---

## 四、你的项目当前状态

- ✅ Git 已安装（v2.53.0）
- ✅ 仓库已初始化
- ✅ 已提交 2 次（README.md + .gitignore）
- ✅ 已推送到 [GitHub](https://github.com/zhoufff/learning-git)

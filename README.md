# CHECKPOINT — 下载

**[→ 点这里下载最新版](https://github.com/denniskong666/checkpoint-releases/releases/latest)**

---

## Windows

1. 下载 `Checkpoint-Windows-*.zip`
2. 解压，运行 **`Checkpoint.exe`**

就这样。

---

## Mac

1. 下载 `Checkpoint-macOS-*.zip`
2. 解压，把 **`Checkpoint.app`** 拖进「应用程序」
3. **打开「终端」，粘贴下面这行，按回车：**

```
xattr -cr /Applications/Checkpoint.app
```

4. 正常打开游戏

### 第 3 步是干什么的？

macOS 会给所有从网上下载的程序打一个「隔离」标记，不处理的话打开时会弹
**「无法打开，因为来自身份不明的开发者」**。上面那行命令就是把这个标记清掉。
它只改这一个 app，不动系统里的任何其他东西。

**如果你把游戏放在了别的地方**（比如桌面或下载文件夹），把命令改成：先在终端里输入
`xattr -cr `（注意最后有个空格），然后**把 Checkpoint.app 直接拖到终端窗口里**，
路径会自动填上，再按回车。

### 不想用终端？

右键点 `Checkpoint.app` → **打开** → 在弹窗里选 **「打开」**。
（必须是右键，直接双击不行。）

---

## 以后怎么更新

包里有一个 **「更新 CHECKPOINT」**：

- Mac：双击 `更新 CHECKPOINT.command`
- Windows：双击 `更新 CHECKPOINT.bat`

它会自己检查有没有新版、下载、替换掉旧版本，Mac 上还会自动清掉上面说的那个隔离标记。
**更新前请先退出游戏。**

打开游戏时如果有新版本，主菜单会提示你。

---

本仓库只存放安装包，不含源代码。

# Windows-Themes-Wallpaper

windows 精美桌面壁纸搜集

## 📁 项目简介

本项目用于搜集和保存 Windows 系统中的精美桌面壁纸。壁纸来源于 Windows 系统主题缓存目录，按编号分类整理。

壁纸在 Windows 系统中的存储路径：

```
%AppData%\Microsoft\Windows\Themes
```

## 🖼️ 壁纸内容

### 编号壁纸

| 系列 | 图片数量 | 文件示例 |
|------|---------|---------|
| 系列 1 | 14 张 | `1-5.png`, `1-7.png`, `1-13.png`, `1-15.png` ... |
| 系列 2 | 13 张 | `2-2.png`, `2-5.png`, `2-10.png`, `2-14.png` ... |
| 系列 3 | 8 张  | `3-2.png`, `3-3.png`, `3-6.png`, `3-31.png` ... |
| 系列 4 | 2 张  | `4-1.png` ... |

部分壁纸存在多个变体版本（如 `1-15.png` / `1-15-2.png`）。

### 特殊命名壁纸

| 文件名 | 说明 |
|--------|------|
| `Neuschwanstein.png` | 新天鹅堡（德国著名城堡） |
| `newyear.png` | 新年主题壁纸 |
| `丹麦瓦埃勒波浪住宅楼.png` | 丹麦瓦埃勒波浪住宅楼 |

> 壁纸共计 **40 张**，存放于 `Images/` 目录下。

## 📸 截图

`Images/Screenshots/` 目录下包含 **17 张** Windows 桌面截图，用于展示壁纸的实际桌面效果。

## 📂 目录结构

```
Windows-Themes-Wallpaper/
├── Images/
│   ├── 1-*.png              # 系列 1 壁纸
│   ├── 2-*.png              # 系列 2 壁纸
│   ├── 3-*.png              # 系列 3 壁纸
│   ├── 4-*.png              # 系列 4 壁纸
│   ├── Neuschwanstein.png   # 新天鹅堡壁纸
│   ├── newyear.png          # 新年壁纸
│   ├── 丹麦瓦埃勒波浪住宅楼.png  # 丹麦建筑壁纸
│   ├── path.txt             # Windows 主题路径说明
│   └── Screenshots/         # 桌面效果截图
├── README.md
└── .gitignore
```

## 💡 使用方法

1. 浏览 `Images/` 目录，选择喜欢的壁纸
2. 下载图片文件
3. 在 Windows 中右键图片 → **设置为桌面背景**

或者将壁纸文件复制到 Windows 主题目录以供系统主题使用：

```powershell
# 打开 Windows 主题目录
explorer %AppData%\Microsoft\Windows\Themes
```

## 📜 许可证

本项目仅供个人学习与欣赏使用，壁纸版权归原作者所有。
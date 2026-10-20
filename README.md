# 中文 LaTeX 简历模板

一个简洁的中文 A4 简历模板，使用 XeLaTeX 编译，适合在 Overleaf 或本地 LaTeX 环境中修改。

## 特性

- 中文排版，A4 页面
- 基于 `ctexart`、`TikZ` 和 `tabularx`
- 可复用的教育经历、项目经历、工作经历和技能模块
- 自带通用头像占位图；也可以替换成自己的证件照
- 不包含真实个人信息，适合作为模板二次编辑

## 快速使用（推荐 Overleaf）

1. 在 GitHub 下载本项目 ZIP，或将仓库导入 Overleaf。
2. 确认主文件为 `main.tex`。
3. 在 Overleaf 的 **Menu → Compiler** 中选择 **XeLaTeX**。
4. 点击 **Recompile**。
5. 将 `main.tex` 中方括号里的提示文字替换为自己的内容。

## 照片

模板默认使用 `generic-photo.png`。如需使用自己的照片，将图片上传到项目根目录并命名为 `photo.jpg`，模板会优先读取 `photo.jpg`。

公开仓库时请勿提交身份证件照、电话号码、个人邮箱、住址等隐私信息。

## 本地编译

安装支持中文的 TeX 发行版后，在项目目录运行：

```bash
xelatex main.tex
```

需要安装的宏包通常包括 `ctex`、`geometry`、`tikz`、`xcolor`、`graphicx`、`array`、`tabularx` 和 `enumitem`。

## 项目结构

```text
chinese-latex-resume-template/
├── main.tex
├── generic-photo.png
├── README.md
├── LICENSE
└── .gitignore
```

## 自定义建议

- 根据目标岗位调整模块顺序。
- 优先写清个人行动、使用的方法和可核实的结果。
- 删除不适用的模块，避免为了填满版面而保留空内容。
- 编译后检查是否超出一页、是否出现过密换行或照片比例失真。

## License

本项目使用 MIT License。使用者可按许可证条款使用、修改和分发。

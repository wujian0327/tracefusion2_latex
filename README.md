# tracefusion2_latex

编译 `main.tex`：

```bash
latexmk -pdf -synctex=1 main.tex
```

PDF、SyncTeX 和辅助文件默认输出到 `target/`，VS Code LaTeX Workshop 也使用该目录。

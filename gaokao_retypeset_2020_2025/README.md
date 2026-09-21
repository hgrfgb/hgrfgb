# 2020--2025年高考数学试卷 LaTeX 重排

范围: 2020年至2025年全部普通高考试卷及上海春季高考试卷, 共60份.

主文件: `main.tex`. 正文: `content/2020` 至 `content/2025`.

图片在构建时从上游 `DxAThing/Gaokao-Math-Problems-Compilation` 获取, 只调用原始位图资源, 不使用重绘图源. 正文源码已剔除上游附加的答案/解析段落, 仅保留试题卷题面.

XeLaTeX 编译后生成 `main.pdf`.

# SZTU 课程论文 LaTeX 空白模板

主模板文件：

- `SZTU_experience_report_template.tex`


资源文件：

- `assets/sztu-logo.png`

## 使用方式

请使用 XeLaTeX 编译：

```powershell
xelatex SZTU_experience_report_template.tex
xelatex SZTU_experience_report_template.tex
```

正文目录需要至少编译两次。模板按原 Word 文档提取的样式设置：

- A4 页面，左/右边距约 3.175 cm，上/下边距约 2.54 cm
- 正文：宋体 12 pt，约 1.5 倍行距，首行缩进 2 字符
- 一级标题：黑体 15 pt，`第一章` 格式
- 二级标题：黑体 15 pt
- 三级标题：黑体 12 pt
- 封面标题：宋体 22 pt 加粗，校徽居中
- 内封题名：微软雅黑 26 pt
- 收尾页：含致谢、参考文献、指导教师批阅意见区和成绩评定页

## 填写字段

在 `.tex` 开头的 `Fill-in fields` 区域修改这些命令即可：

```tex
\providecommand{\CourseCode}{...}
\providecommand{\CourseName}{...}
\providecommand{\ReportTitle}{...}
\providecommand{\ClassName}{...}
\providecommand{\StudentName}{...}
\providecommand{\StudentID}{...}
\providecommand{\TeacherName}{...}
\providecommand{\CoverDate}{...}
\providecommand{\AuthorSchool}{...}
\providecommand{\InnerDate}{...}
\providecommand{\Keywords}{...}
```

如果编译环境没有宋体、黑体、仿宋、微软雅黑，可在模板字体映射区域替换为本机已安装字体。

## 隐私

请勿提交本地 preview、PDF、辅助编译文件或视觉对比图。这些文件可能包含原始论文内容和个人信息，已经在 `.gitignore` 中默认排除。

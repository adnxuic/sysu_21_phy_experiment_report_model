# 中山大学物理学大二上学期实验报告latex模板



## 文献引用



### 1 使用bibtex

#### 1.1 创建.bib文件
* 在.tex文件所在目录下创建一个.bib文件，例如`reference.bib`。
* 在.bib文件中添加文献信息，例如：

```bib
@article{label,
  author = {作者},
  title = {文章标题},
  journal = {期刊名称},
  year = {年份},
```
* 在一些文献的网站上可以导出文献的bib格式信息，例如[PRD](https://link.aps.org/doi/10.1103/PhysRevD.81.033005)中的Export Citation。

#### 1.2 在.tex文件中引用文献
* 在.tex文件中引用文献的地方添加`\cite{label}`，其中`label`为在.bib文件中为该文献添加的标签。
* 在.tex文件中添加`\bibliographystyle{plain}`。
* 在.tex文件中适当位置添加`\bibliography{reference}`，其中`reference`为.bib文件的文件名。

如下所示：

```tex
\newpage
\bibliographystyle{plain}
\bibliography{reference}
% 一般在文档的末尾添加，即\end{document}前
```

# 其他



## 1. 计算不确定度的小程序

[UncertaintyCalculation](https://github.com/adnxuic/UncertaintyCalculation)

## 2. excel转latex三线表的小程序

[excel_latex](https://github.com/adnxuic/excel_latex)

## 3. 关于其他latex的基础模板如列表，表格等持续更新

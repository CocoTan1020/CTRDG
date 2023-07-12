# CTRDG
## 中文文本阅读难度分级数据集(Chinese Text Reading Difficulty Grading dataset)
## 数据说明:
text \t label
text:中文阅读文本
label:0-5,分别代表该中文阅读文本的可读性等级(一级-六级)
训练集：train.txt(4576个)
验证集：dev.txt(572个)
测试集样例：test.txt(573个)

## 数据来源:
数据集来自汉语水平考试(HSK)相关材料。
具体为北京语言大学出版社的教材《HSK 标准教程》与配套练习册《HSK 标准教程练习册》、孔子学院总部与国家汉办编制的《新汉语水平考试样卷》与《新汉语水平考试真题集》，共计 249 份材料。
借 助 CnOCR 文 字 识 别 (Optical Character Recognition，OCR)工具包，从上述教材中抽取出每单元的课文正文，从上述练习册、样卷、真题集中抽取部分阅读文章。


## 浙江大学研究生硕士(博士)学位论文LaTeX模板
作者:
[Monster](http://github.com/skychan)、
[Hamburger](https://github.com/githamburger)

## 1、简介

为了方便学位论文的排版，让作者专心于内容，根据[《浙江大学研究生学位论文编写规则》](http://grs.zju.edu.cn/UserFiles/File/xkjsc/xwglb/wenjian/%E6%B5%99%E6%B1%9F%E5%A4%A7%E5%AD%A6%E7%A0%94%E7%A9%B6%E7%94%9F%E5%AD%A6%E4%BD%8D%E8%AE%BA%E6%96%87%E7%BC%96%E5%86%99%E8%A7%84%E5%88%99.doc)，并结合实际要求，设计相应的LaTeX模版。

目前主要以机械学院的要求为主，由于不同学院有各自不同的要求，所以之后会通过参数选择的方式，进行学院间的要求切换，大致就是这样吧。

## 2、编译方法

__windows__:

run make.bat，并按提示选择所需。

__Linux__:

	$ cd zju_thesis
	$ make

## 3、完成情况
- [x] 主题框架
- [x] 页面设置
- [x] 章节标题设置
- [ ] 公式、图表样式
- [ ] 定理环境
- [ ] 抄录环境
- [ ] 参考文献样式设计
- [x] 封面设置
- [x] 题目页面
- [ ] 勘误页面
- [x] 单双页设置
- [x] 缩写、符号清单、术语表页面

## 4、欢迎参与

目前该项目基本雏形已成，至少算是能用了吧，一些细节需要完善，欢迎大家fork~

## 5、注意事项

由于重写了\matetitle 用于封面的生成，估计里面有些地方做的不好，所以编译速度有点慢。这个问题需要解决一下。

由于时间和能力有限，故该模板可能与学院要求的格式不尽相同。
建议使用TeXLive，并采用XeLaTeX进行编译。
作者不对使用该模板所造成的任何后果负责，但欢迎提供修改意见，以帮助我们完善该模。

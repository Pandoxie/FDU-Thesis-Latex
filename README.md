##Latex Thesis for Fudan University
该GIT库提供了基本满足**复旦大学**博士（硕士）毕业论文格式要求的Latex模板。

主要包含：**FDUbib.bst**（参考文献风格），**FDUThesis.sty**（正文风格）两部分文件。  
**Thesis.tex**给出了上述文件的使用框架，仅供参考。  
此外，**Book-Cover.tex**还提供了封面的源码，请自行修改直接编译使用。

##Usage
建议首先下载**DEMO**文件夹下内容进行测试：
-  运行**xelatex**编译器编译**thesis.tex**
-  运行**Bibtex**编译器生成参考文献索引
-  **再次/多次**运行**xelatex**生成交叉引用和参考文献等 

***
DEMO文件夹提供了使用该模板的一篇删减版博士论文，仅供不熟悉Latex使用的同学参考。鉴于水平有限，可能不免贻笑大方。
~~由于本人论文还:bangbang:**没有**:bangbang:提交教务处审批，各位自重:kissing_heart:~~

## Caveat
-  **FDUThesis**加载了较多的个性化宏包，请自行根据需要进行删减
-  由于本人对相对臃肿的**CJK**宏包比较反感，所以仅采用**xecjk**对中文进行基本处理
-  在字体的选择方面，由于本人采用的为Mac平台，所以选择了自己比较偏好的Songti SC而非SimSun（不知何种原因，SimSun排版出来基线好像会对不齐，并且觉得看了不开心）。Windows平台的童鞋若没有安装相应字体，请修改 **CJK Font Setup** 下面的字体名称
-  鉴于时间限制，废话不能过多。Latex的乐趣就在于自己摸索，本模板的最大作用也莫过于抛砖引玉，**Enjoy**:coffee:

***
注：参考文件风格模板（**GB-T 7714-2005**）借鉴了**thuthesis**的基本框架，在此对该模板的制作者致敬！  
**Syriana**, 嗷嗷（这算鸣谢么）  
**Pandoxie-BiB.bib**提供了参考文献录入示例，原数据为**EndNote**导出。  
**BibTeX Export-Zh.ens**提供了本人使用的**EndNote**导出风格插件（忘记修改了什么捏:grimacing:，仅供参考）。  
**Thesis.ist**提供了索引的风格定义，可根据实际需要进行修订。

## Git-Phobic
-  **FDUThesis**还有自己的[Git Page](http://pandoxie.github.io/FDU-Thesis-Latex/)，提供懒虫直接下载。
-  欢迎访问Pandoxie的[个人网站](http://www.pandoxie.com)或直接参与Git互动让FDU-Latex更加实用、强大。

## License

The content of this project itself is licensed under the [Creative Commons Attribution 3.0 license](http://creativecommons.org/licenses/by/3.0/us/deed.en_US)  
The underlying source code used to format and display that content is licensed under the [MIT license](http://opensource.org/licenses/mit-license.php).

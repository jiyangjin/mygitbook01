#第一部分 语法
##标题
标题分为6层标题，在Markdown下，分别表示如下：
#this is the 一级标题
##this is the 二级标题
###this is the 三级标题
####this is the 四级标题
#####this is the 五级标题
######this is the 六级标题
##列表
在Markdown 下，列表的显示只需要在文字前加上 - 或 * 即可变为无序列表，有序列表则直接在文字前加1. 2. 3. 符号要和文字之间加上一个字符的空格。

###无序列表
* 1
* 2
* 3
###有序列表
1. 1
2. 2
3. 3

##引用
引用一小段别处的句子，只需要在文本前加入>这种尖括号（大括号）即可
>这是一段引用的语句
##图片与链接
插入图片为
!\[](){ImgCap}{/ImgCap}
插入链接
\[]()
#####这里插入了百度的链接
[www.baidu.com](http://www.baidu.com)
#####这里插入了一个图片
![猫咪](http://image.baidu.com/search/down?tn=download&word=download&ie=utf8&fr=detail&url=http%3A%2F%2Fimg4q.duitang.com%2Fuploads%2Fitem%2F201108%2F24%2F20110824143814_4zFQh.jpg&thumburl=http%3A%2F%2Fimg1.imgtn.bdimg.com%2Fit%2Fu%3D933124850%2C3168176999%26fm%3D23%26gp%3D0.jpg)


##粗体与斜体
用两个 * 包含一段文本就是粗体的语法，用一个 * 包含一段文本就是斜体的语法。
*斜体*  **粗体**

##表格
比较复杂，暂时不写
>| Tables| Are|Cool|

##应用代码（代码框）
`	public ActionForward getList(ActionMapping mapping, ActionForm form,
			HttpServletRequest request, HttpServletResponse response) {
		String forward = setForward(request, "list");
		getPersonList(request);
		getOrganList(request);
		request.setAttribute("pageMaxnum", pageMaxnum);
		return mapping.findForward(forward);
	}`

##分隔线
分隔线为三个*，如下
***
## java-jsp-note
##### 语法

`<%@ page contentType="text/html;charset=UTF-8" language="java" %>`

`<% 代码片段 %>`

##### 声明

`<%! declaration; [ declaration; ]+ ... %>`

#####　表达式

`<%= 表达式 %>`

##### 注释

<%-- 该部分注释在网页中不会被显示--%> 
<!-- 注释 -->


##### 指令

`<%@ directive attribute="value" %>`

这里有三种指令标签：

`<%@ page ... %> 定义页面的依赖属性，比如脚本语言、error页面、缓存需求等等`

`<%@ include ... %>	包含其他文件`

`<%@ taglib ... %>	引入标签库的定义，可以是自定义标签`

##### 内置对象

`request	HttpServletRequest类的实例`

`response	HttpServletResponse类的实例`

`out	PrintWriter类的实例，用于把结果输出至网页上`

`session	HttpSession类的实例`

`application	ServletContext类的实例，与应用上下文有关`

`config	ServletConfig类的实例`

`pageContext	PageContext类的实例，提供对JSP页面所有对象以及命名空间的访问`

`page	类似于Java类中的this关键字`

`Exception	Exception类的对象，代表发生错误的JSP页面中对应的异常对象`


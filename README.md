# holiday
假期学习唯创
#html课程
<html>
	<head>
    <meta charset="utf-8">
	<title>淘宝</title>
    <meta name="keywords" content="鲜花，好多鲜花">
    <meta name="description" content="鲜花速递">
	</head>
    <body>
    <!-- 标签 -->
    <h1>这是加粗的字体的标签</h1>
    <h2>这是加粗的字体</h2>
    <h3>这是加粗的字体</h3>
    <h4>这是加粗的字体</h4>
    <h5>这是加粗的字体</h5>
    <h6>这是加粗的字体</h6>
	<!-- 锚点 -->
    <a href="http://www.baidu.com" target="_blank">百度一下</a>
    <!-- 有序列表 -->
    <ol>
    	<li>有序列表1</li>
    	<li>有序列表2</li>
    	<li>有序列表3</li>
    	<li>有序列表4</li>
    	<li>有序列表5</li>
	</ol>
    <ul>
        <li>无序列表1</li>
        <li>无序列表2</li>
        <li>无序列表3</li>
        <li>无序列表4</li>
		<li>
       	 <a href="http://www.baidu.com">打开百度</a>
        </li>
        <li>
        	<h1>这是一个h1标签</h1>
        </li>
    </ul>
    <!-- 路径：绝对路径 相对路径 -->
    <img src="1.jpg" alt="加载图片失败"      title="这是一个团队的图片">
    <img src="http://www.siaedu.net/Public/images/courses/index/icon_2.png" title="这是百度上面的图片">
    
    <!-- 表格 -->
    <table border="1">
    	<tr>
        	<td colspan="2">11</td>
            
        </tr>
        <tr>
        	<td rolspan="2">33</td>
            <td>44</td>
        </tr>
    </table>
    <p>一篇文章</p>
    <p>一篇文章</p>
    <p>一篇文章</p>
    <p>一篇文章</p>
    <p>一篇文章</p>
    <!-- 布局标签 -->
    <div>div+css</div>
    <!-- 布局标签 -->
    <div>div+css</div>
     <div>div+css</div>
    <span>这是一个span标签</span>
    <span>这是一个span标签</span>
    </body>
</html>
<!-- 
块级元素（block）：h1~h6 p div ul ol li自己占一行 宽度不设置的情况下是充满父元素的
行级元素（inline）:span a 行级元素和行级元素在一行，不能设置宽高  宽高是内容撑开的

-->




#css课程
<html>
	<head>
    <meta charset="utf-8">
		<title>css</title>
        <!-- 内部样式-->
        <style>
		h1{
			background:red;
			color:yellow;
			}
	    #p1{
			background:#fff;
			}
		#p2{
			font-size:50px;
			
			}
		span{
			background:#0F0;
			width:200px;
			height:200px;
				}
		div{
			width:200px;
			height:200px；;
			background:#ff0000;
			}
			.cls{
				background:#f00;
				color:#0f0;
				}
			#user-info{
				width:2450px;
				height:1400px;
				background:#ccc url(2.jpg) no-repeat left top ;
				background-color:#ccc;
				background-image:url(2.jpg);
				background-repeat:no-repeat;
				background-position:center;
				}
        </style>
        <!--外部样式使用最多-->
       <!-- <link rel="stylesheet" href="唯创css.css">-->
	</head>
    <body>
    <!-- 内联样式使用最少 -->
    <h1>窝在家里</h1>
    <div style="background: red;color: green;">全栈培训</div>
     <p id="p1">自己学习</p>
     <span class="cls">这是一个span</span>
     <div>
     <p id="p2">pppp</p>
     </div>
     <div id="user-info">divdivdiv</div>
    </body>
</html>
<!--

rgb:red green blue
css的选择器
1.标签、元素选择器  div{}  p{}
2.id选择器,是唯一的，不可以重复的   #id{}
3.class类选择器  可以重复的  .class{}
-->
##练习
<html>
    <head>
    	<meta charset="utf-8">
    	<title>lianxi</title>
    <style>
		#market{background-color:#f44b3b;
			weight:200px;
			height:30px;
			line-height:50px;
			color:#fff;
			text-align:center;
			
		}
    </style>
    </head>
    
    <body>
    <h2 id="market">主题市场</h2>
    </body>
</html>

# 前端学习之路


长话短说，跟着B站学hmtl+css+js,xian,现阶段学习到了css中的元素定位，视频参考[《字节大佬一周讲完的前端web……》](https://www.bilibili.com/video/BV1gY4y1U78C/?spm_id_from=333.1007.top_right_bar_window_view_later.content.click&vd_source=103c23a847485c1457bb3033abcc9ce5),**当前学习进度24%（34/139）。**

## 一、html的学习记录
&emsp;&emsp;[效果演示](</one day.html>)，代码如下：

{{< admonition type=tip title="标题设置，点击可打开查看" open=false >}}
    <h1>一级标题</h1>
    <h2>二级标题</h2>
    <h3>三级标题</h3>
    <h4>四级标题</h4>
    <h5>五级标题</h5>
    <h6>六级标题</h6>
{{< /admonition >}}
呈现的效果如下：
{{< raw >}}
    <h1>一级标题</h1>
    <h2>二级标题</h2>
    <h3>三级标题</h3>
    <h4>四级标题</h4>
    <h5>五级标题</h5>
    <h6>六级标题</h6>
{{< /raw >}}

{{< admonition type=tip title="常用文本标签，点击可打开查看" open=false >}}
        <p>这是段落符号，<br>单换行符  </p>
        <p>下面是分割线演示  </p>
        <hr color="orange" width="300px" size="10px" align="left" />    
        <em> em 定义着重文字</em><br>
        <b> b 定义粗体文本</b><br>
        <i> i 定义斜体字</i><br>
        <strong>strong定义加重语气</strong><br>
        <del>del定义删除字</del><br>
        <span>span元素没有特定的含义</span></p>
{{< /admonition >}}
呈现的效果如下：

{{< raw >}}
        <p>这是段落符号，<br>单换行符  </p>
        <p>下面是分割线演示  </p>
        <hr color="orange" width="300px" size="10px" align="left" />
        <em> em 定义着重文字</em><br>
        <b> b 定义粗体文本</b><br>
        <i> i 定义斜体字</i><br>
        <strong>strong定义加重语气</strong><br>
        <del>del定义删除字</del><br>
        <span>span元素没有特定的含义</span></p>
{{< /raw >}}

{{< admonition type=tip title="常用元素引用，点击可打开查看" open=false >}}
    <p> img 标签定义HTML页面中的图像属性：<br>
        ①src：路径（图片地址与名字）<br>
        ②alt：规定图像的替代文本<br>
        ③width：规定图像的宽度<br>
        ④height：规定图像的高度<br>
        ◎title：鼠标悬停在图片上给予提示</p>
    <img src="https://media.st.dl.eccdnx.com/steam/apps/1143810/capsule_616x353.jpg?t=1692123340" width="400px">
    
    <p>下面是超链接，用 a 来表达</p>
    <a href="https://niujixiang.github.io">Qingm的博客</a>
{{< /admonition >}}
呈现的效果如下：

{{< raw >}}
    <img src="https://media.st.dl.eccdnx.com/steam/apps/1143810/capsule_616x353.jpg?t=1692123340" width="400px">    
    <p>下面是超链接，用 a 来表达</p>
    <a href="https://niujixiang.github.io">Qingm的博客</a>
{{< /raw >}}

{{< admonition type=tip title="有序和无序列表，点击可打开查看" open=false >}}
<ol>
        <li>动物</li>
        <li>植物
            <ol type="a">
                <li>苹果</li>
                <li>香蕉</li>
            </ol>
         <li>无机物</li>
        </li>
    </ol>
 
<ul type="circle">
        <li>啊好看哇好</li>
        <li>哈伦裤我电话</li>
        <li>观看交换空间环境</li>
        <li>哈共和国</li>
</ul>

{{< /admonition >}}
呈现的效果如下：

{{< raw >}}
有序列表：
<ol>
        <li>动物</li>
        <li>植物
            <ol type="a">
                <li>苹果</li>
                <li>香蕉</li>
            </ol>
         <li>无机物</li>
        </li>
    </ol>
无序列表：
<ul type="circle">
        <li>啊好看哇好</li>
        <li>哈伦裤我电话</li>
        <li>观看交换空间环境</li>
        <li>哈共和国</li>
</ul>   

{{< /raw >}}

{{< admonition type=tip title="表格属性，点击可打开查看" open=false >}}
    <p>表格组成与特点,表格：table 行：tr单元格（列）：td  <br>
        快速生成表格结构：table>tr*2>td*5｛这里填内容｝<br>
        表格属性①border：设置表格的边框  width：设置表格的宽度 height：设置表格的高度</p>
    <table border="2" width="300" height="200">
        <tr>
            <td>单元格</td>
            <td>单元格</td>
            <td>单元格</td>
        </tr>
        <tr>
            <td>单元格</td>
            <td>单元格</td>
            <td>单元格</td>
        </tr>
        <tr>
            <td>单元格</td>
            <td>单元格</td>
            <td>单元格</td>
        </tr>
    </table>
    <p>单元格合并，水平合并(保左删右)：colspan   垂直合并（保上删下）：rowspan</p>
    <table border="2" width="500" height="200">
        <tr>
            <td>单元格1</td>
            <td>单元格2</td>
            <td>单元格3</td>
            <td>单元格4</td>
            <td>单元格5</td>
        </tr>
        <tr>
            <td colspan="2">单元格6单元格7</td>
            <td>单元格8</td>
            <td>单元格9</td>
            <td>单元格10</td>
        </tr>
        <tr>
            <td>单元格11</td>
            <td>单元格12</td>
            <td>单元格13</td>
            <td>单元格14</td>
            <td rowspan="2">单元格15单元格20</td>
        </tr>
        <tr>
            <td>单元格16</td>
            <td>单元格17</td>
            <td>单元格18</td>
            <td>单元格19</td>
        </tr>
        <tr>
            <td>单元格21</td>
            <td>单元格22</td>
            <td>单元格23</td>
            <td>单元格24</td>
            <td>单元格25</td>
        </tr>
    </table>

{{< /admonition >}}
呈现的效果如下：

{{< raw >}}
    <p>表格组成与特点,表格：table 行：tr单元格（列）：td  <br>
        快速生成表格结构：table>tr*2>td*5｛这里填内容｝<br>
        表格属性①border：设置表格的边框  width：设置表格的宽度 height：设置表格的高度</p>
    <table border="2" width="300" height="200">
        <tr>
            <td>单元格</td>
            <td>单元格</td>
            <td>单元格</td>
        </tr>
        <tr>
            <td>单元格</td>
            <td>单元格</td>
            <td>单元格</td>
        </tr>
        <tr>
            <td>单元格</td>
            <td>单元格</td>
            <td>单元格</td>
        </tr>
    </table>
    <p>单元格合并，水平合并(保左删右)：colspan   垂直合并（保上删下）：rowspan</p>
    <table border="2" width="500" height="200">
        <tr>
            <td>单元格1</td>
            <td>单元格2</td>
            <td>单元格3</td>
            <td>单元格4</td>
            <td>单元格5</td>
        </tr>
        <tr>
            <td colspan="2">单元格6单元格7</td>
            <td>单元格8</td>
            <td>单元格9</td>
            <td>单元格10</td>
        </tr>
        <tr>
            <td>单元格11</td>
            <td>单元格12</td>
            <td>单元格13</td>
            <td>单元格14</td>
            <td rowspan="2">单元格15单元格20</td>
        </tr>
        <tr>
            <td>单元格16</td>
            <td>单元格17</td>
            <td>单元格18</td>
            <td>单元格19</td>
        </tr>
        <tr>
            <td>单元格21</td>
            <td>单元格22</td>
            <td>单元格23</td>
            <td>单元格24</td>
            <td>单元格25</td>
        </tr>
    </table> 

{{< /raw >}}

{{< admonition type=tip title="用户交互，点击可打开查看" open=false >}}
<p>form 用户交互<br> 
        属性说明<br>
        action服务器地址  name表单名称<br>
        method中Get和Post的区别 数据提交方式，get把提交的数据url可以看到，post看不到
        get一般用于提交少量数据，post用来提交大量数据</p>
<p>一个完整的表单包含三个基本组成部分：表单标签form、表单域input、表单按钮button </p>

<form>
    用户名: <input type="text" >
    密码：<input type="password">
    <input type="submit" value="登录/注册">
    <button>这是按钮</button>
</form>

{{< /admonition >}}
呈现的效果如下：

{{< raw >}}
<form>
    用户名: <input type="text" ><br>
    密&ensp;码：<input type="password"><br>
    &emsp;<input type="submit" value="登录/注册">
    &emsp;&emsp;&emsp;<button>忘记密码</button>
</form> 

{{< /raw >}}

此外还有一些关于div容器等方面的一些内容，可以去看视频。

## 二、css的学习记录
&emsp;css属于是网页布局和美化，确实能让页面好看不少。可以先看以下效果吧
* [《图片和表格》](/html/css-图片和表格属性.html)
* [《文字属性》](/html/css-文字属性.html)
* [《盒子模型》](/html/css盒子模型.html)
* [《定位和圆角和阴影》](/html/定位-圆角和阴影.html)
* [《css动画》](/html/动画.html)
{{< admonition type=tip title="css动画，点击可打开查看" open=false >}}

    <style>
        .box1{
            width: 200px;
            height: 200px;
            background-color: red;
            animation: my1donghua 5s linear 0s infinite;
        }
        .box1:hover{
            animation-play-state: paused;
        }
        @keyframes my1donghua{
            0%{
               width: 200px;
               height: 200px;
               background-color: red;
            }
            25%{
                width: 600px;
                height: 200px;
                background-color: green;
            }
            50%{
                width: 600px;
                height: 400px;
                background-color: green;
                background-image: url("https://picx.zhimg.com/80/v2-23d671bf74a246c54b1256bd2322d461_720w.webp?source=1940ef5c");
                background-size: cover;
            }
            75%{
                width: 200px;
                height: 400px;
                background-color: green;
            }
            100%{
                width: 200px;
                height: 200px;
                background: red;
            }
        }
        .box2{
            width: 500px;
            height: 400px;
            margin: 40px auto;
            background-color: #2b92d4;
            border-radius: 20px;
            box-shadow: 0 1px 2px rgba (0, 0, 0, 3);
            animation: breathe 2700ms ease-in-out infinite alternate;
        }
        @keyframes breathe {
            0%{
                opacity: 0.2;
                box-shadow: 0 1px 2px rgba (255, 255, 255, 0.1)
            }
            50%{
                opacity: 0.5;
                box-shadow: 0 1px 2px rgba (18, 190, 84, 0.76)
            }
            100%{
                opacity: 1;
                box-shadow: 0 1px 30px rgba (59, 255, 255, 1)
            }
        }
    </style>
</head>
<body>
    <div class="box1"></div>
    <h3>呼吸效果</h3>
    <div class="box2"></div>

{{< /admonition >}}
呈现的效果如下：

{{< raw >}}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .box1{
            width: 200px;
            height: 200px;
            background-color: red;
            animation: my1donghua 5s linear 0s infinite;
        }
        .box1:hover{
            animation-play-state: paused;
        }
        @keyframes my1donghua{
            0%{
               width: 200px;
               height: 200px;
               background-color: red;
            }
            25%{
                width: 600px;
                height: 200px;
                background-color: green;
            }
            50%{
                width: 600px;
                height: 400px;
                background-color: green;
                background-image: url("https://picx.zhimg.com/80/v2-23d671bf74a246c54b1256bd2322d461_720w.webp?source=1940ef5c");
                background-size: cover;
            }
            75%{
                width: 200px;
                height: 400px;
                background-color: green;
            }
            100%{
                width: 200px;
                height: 200px;
                background: red;
            }
        }
        .box2{
            width: 300px;
            height: 300px;
            margin: 20px auto;
            background-color: #2b92d4;
            border-radius: 20px;
            box-shadow: 0 1px 2px rgba (0, 0, 0, 3);
            animation: breathe 2700ms ease-in-out infinite alternate;
        }
        @keyframes breathe {
            0%{
                opacity: 0.2;
                box-shadow: 0 1px 2px rgba (255, 255, 255, 0.1)
            }
            50%{
                opacity: 0.5;
                box-shadow: 0 1px 2px rgba (18, 190, 84, 0.76)
            }
            100%{
                opacity: 1;
                box-shadow: 0 1px 30px rgba (59, 255, 255, 1)
            }
        }
    </style>
</head>
<body>
    <div class="box1"></div>
    <h3>呼吸效果:</h3>
    <div class="box2"></div>
        
</body>
</html>

{{< /raw >}}


## 三、未完待续



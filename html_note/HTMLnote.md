# HTML入门

### 所需软件/插件

VScode 

HTML CSS Support + LiveServer(可以看到实时网页变化)

## introduction
` HTML全称Hypertext Markup Language(超文本标记语言) 它定义了网页内容的含义和结构。`
### 1.常见文本标签  

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>常见文本标签</title>
</head>
<body>
<h1>一级标签</h1>
<h2>二级标签</h2>
<h3>三级标签</h3>
<h4>四级标签</h4>
<h5>五级标签</h5>
<h6>六级标签</h6>
<p>这是一个段落标签</p>
<p>更改文本样式：<b>加粗</b> <i>斜体</i> <u>下划线</u> <s>删除线</s> </p>
<p>更改文本颜色：<font color="red">红色</font> <font color="blue">蓝色</font> <font color="green">绿色</font> </p>
<p>更改文本大小：<font size="1">1号字体</font> <font size="2">2号字体</font> <font size="3">3号字体</font> </p>
<p>更改文本字体：<font face="Arial">Arial</font> <font face="Courier">Courier</font> <font face="Georgia">Georgia</font> </p>
<p>更改文本背景：<span style="background-color: red;">红色</span> <span style="background-color: blue;">蓝色</span> <span style="background-color: green;">绿色</span> </p>
<ul>
    <li>无序列表1</li>
    <li>无序列表2</li>
    <li>无序列表3</li>
</ul>
<ol>
    <li>有序列表1</li>
    <li>有序列表2</li>
    <li>有序列表3</li>
</ol>
<table>
    <tr>
        <th>表头1</th>
        <th>表头2</th>
        <th>表头3</th>
    </tr>
    <tr>
        <td>表格1</td>
        <td>表格2</td>
        <td>表格3</td>
    </tr>
    <tr>
        <td>表格4</td>
        <td>表格5</td>
        <td>表格6</td>
    </tr>
    <tr>
        <td>表格7</td>
        <td>表格8</td>
        <td>表格9</td>
    </tr>
</table>
</body>
</html>
```

效果图：

![](../../hututao's note/assets/屏幕截图 2024-07-08 200509.png)



### 2.标签属性 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>标签属性</title>
</head>
<body>
    <a href="https://www.baidu.com" target="_blank">这是一个超链接</a>
    <br>
    <img src="13deb271ffa74a3c88592c909ee5d3a7.png" alt="" width="200" height="150">
    <br>
    <img src="13deb277.png" alt="该图片无法显示" width="200" height="300">
</body>
</html>
```

![](../../hututao's note/assets/屏幕截图 2024-07-08 200747.png)

### 3.块元素与行内元素 

  1. 常见块元素

    `<div>` `<p>` `<h1~h6>` `<ul>` `<ol>` `<li>` `<table>` `<form>`
  2. 常见行内元素
      `<span>` `<strong>` `<a>` `<em>` `<img>` `<br>` `<input>`

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML区块</title>
</head>
<body>
    <div class="nav">
        <a href="#">链接1</a>
        <a href="#">链接2</a>
        <a href="#">链接3</a>
        <a href="#">链接4</a>
    </div>
    <div class="content">
        <h1>标题1</h1>
        <p>内容1</p>
        <p>内容2</p>
        <p>内容3</p>
        <p>内容4</p>
    </div>
    <span>这是第1个span标签</span>
    <span>这是第2个span标签</span>
    <span>这是第3个span标签</span>
    <span>这是第4个span标签</span>
    <hr>
    <span>链接点击这里<a href="#">链接5</a></span>
</body>
</html>
```

![](../../hututao's note/assets/屏幕截图 2024-07-08 200838.png)

### 4.表单 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML表单</title>
</head>
<body>
    <form>
        <label for="username">用户名：</label>
        <input type="text" id="username" placeholder="请输入内容">
        <br>
        <label for="pwd">密码：</label>
        <input type="password" id="pwd" placeholder="请输入密码">
        <br>
        <label >性别</label>
        <input type="radio" name="gender">男
        <input type="radio" name="gender">女
        <br>
        <label >爱好</label>
        <input type="checkbox" name="hobby">唱歌
        <input type="checkbox" name="hobby">跳舞
        <input type="checkbox" name="hobby">rap
        <input type="checkbox" name="hobby">篮球
        <br>
        <input type="submit" value="上传">
    </form>
</body>
</html>
```

![](../../hututao's note/assets/屏幕截图 2024-07-08 201141.png)


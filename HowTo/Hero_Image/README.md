![](../../images/hero_image.png)


代码清单:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
    
        /* body, html 默认高度为0, 所以设置一下高度, body的子元素的高度是以父元素的百分比设置的 */
        body, html {
            height: 100%;
            margin: 0;
        }
 
        .hero-image {
            background-image: url("photographer.jpg");
            height: 50%;
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            position: relative;
        }
 
        /* 此处涉及到两个居中布局, .hero-text的div块元素居中, 以及div中的文本居中, 这是两种不同的技术*/
        .hero-text {
            text-align: center; /* 文本居中 */
            
            
            /* 下面4行代码实现 div 块元素居中*/
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            
            
            color: white;
        }
 
        .hero-text button {
            border: none;
            outline: 0;
            display: inline-block;
            padding: 10px 25px;
            color: black;
            background-color: #ddd;
            text-align: center;
            cursor: pointer;
        }
 
        .hero-text button:hover {
            background-color: #555;
            color: white;
        }
    </style>
</head>
<body>
 
<div class="hero-image">
    <div class="hero-text">
        <h1 style="font-size:50px">I am John Doe</h1>
        <p>And I'm a Photographer</p>
        <button>Hire me</button>
    </div>
</div>
 
<p>Page Content..</p>
 
</body>
</html>
```
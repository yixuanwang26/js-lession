# js-lession

[lessions](http://www.fgm.cc/learn/)

### 学习记录
***
#### lession1 
1. text-align:center 可以使子元素（文字）居中显示，如果需要使div类元素居中显示，则设置设置宽度不占满父元素，并且margin:0px auto
2. > 1 === 1 && (console.log('1 === 1')); 
 
    相当于
   > if(1===1){
       console.log('1===1');
    }


3. 如果同一类元素的绑定方法中实现效果相同，可循环该元素实现绑定。
#### lession2
1.  > #select li.current {
        background: #fff !important;
    }

    选到id是select元素里的 类为current的li元素，li和.current 之间不能有空格。
2. 简短便利循环： for in 
#### lession3
1. > var divEle = document.getElementsByTagName('div')[0];

    getElementsByTagName即使只能得到唯一的一个dom元素，其类型也是一个数组，不同于getElementById 只得到一个对象
#### lession4
1. > li:hover {
         background: rgb(190, 191, 241);
      }

    伪类和元素中间不能有空格。
#### lession8
1. 清除float漂浮的四种方法
   * 对父级设置固定高度

   * 在父级之内，浮动元素之外增加一个<div style="clear:both"></div>

   * 父级增加样式，overflow:hidden

   * 在父级增加伪类after
#### lession9
1. 添加gif图片为加载动画

  > background:#fff url(../asset/loading.gif) 50% 50% no-repeat;
  
  no-repeat去除了平铺效果，背景颜色添加#fff，设置透明度opacity:0.4;可以调出遮罩效果。
  
  50% 50% 固定位置到中心。
#### lession10
1. 对a元素设置宽高不起作用，增加样式display:block之后生效。
   因为a元素是行内元素。
##### 对于css元素类型的整理
* 替换元素&&&非替换元素

    替换元素就是浏览器根据元素的标签或者属性来决定元素要显示的内容，一般有`<input>` `<img>` `<textarea>` `<select>` `<object>`

    非替换元素就是元素中包含了什么就显示什么。
* 块级元素和行内元素

    块级元素就是横向上充满父级，独成一行,典型的块级元素有`<div>` `<p>` `<h1>`等。
    浮动元素会自动变为block元素.

    行内元素不形成新元素块，左右可以有其他元素，比如`<a>` `<span>` `<strong>`

* 元素样式设定

  块级元素和行内替换元素 width,height,margin和padding都可生效，遵循标准css盒子模型

  行内非替换元素 
              
        width,height不起作用，只能通过line-height来设置高度
     
        padding左右起作用，上下不起作用，对于有背景色和内边距的行内非替换元素，背景会延伸，但是行高不变

        margin左右起作用，上下不起作用。

  



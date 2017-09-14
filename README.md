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

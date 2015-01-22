## css
1. [css Shape](http://zhuanlan.zhihu.com/FrontendMagazine/19774074) [css Shape online tools](http://bennettfeely.com/clippy/)   

   `.element{
        shape Property:shape Function(/* parameters */);
   }`
   * shape Property
       
       形状函数接受坐标点或偏移量、或图片的Alpha通道来定义

       1. shape-outside:限制形状周围的内容
       2. shape-inside：限制形状内部的内容

   * shape Function
       
       形状函数接受坐标点或偏移量、或图片的Alpha通道来定义

       1. circle
       2. ellipse
       3. inset
       4. polygon

   **必须满足一下条件css shape 才会生效**

       1. 元素必须是浮动的
       2. 元素必须有确定的尺寸
    
2. 响应式图片srcset全新释义sizes属性、w描述符 [参考](http://www.zhangxinxu.com/wordpress/2014/10/responsive-images-srcset-size-w-descriptor/)

    `<img src="..." srcset="mm-width-128px.jpg 128w,mm-width-256px.jpg 256w,mm-width-512px.jpg" sizes="(max-width:360px) 340px,128px" />`
    
    `<img src="..." srcset="mm-width-128px.jpg 128w,mm-width-256px.jpg 256w,mm-width-512px.jpg" sizes="(max-width:360px) calc(100vw - 20px),128px" />`
   
    
    

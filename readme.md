-html2canvas 因为移动端
网页分享  小程序 不能直接分享到朋友圈
canvas 将整个网页或者一部分网页转成canvas

html2canavs(dom,{
    onrendered:function(canvas){
        显示  css
    }
})

-svg 是图片
假如他能将整个dom  画在它内部的话
foreignObject  svg=>html

-window.getcomputedStyle(dom,null)
任何节点的css属性值都能拿到 
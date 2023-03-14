

# scroll



#### scroll事件源是windows



#### scrollTop：指的是某个盒子内容距离顶部多少，返回值不带单位，只能用在盒子里面的滚动条

#### scrollLeft：指的是某个盒子内容靠左边多少，返回值不带单位

#### scrollHeight：指的是某个盒子总共高度，不含边框，返回值不带单位

#### scrollWidth:指的是某个盒子总共宽度，不含边框，返回值不带单位

#### offsetTop：指的是拿到一个元素距离顶部距离，它以带有父亲定位为准，如果没有父亲或者父亲没有定位，则以body为准

#### offsetLeft：指的是拿到一个元素距离左边距离，它以带有父亲定位为准，如果没有父亲或者父亲没有定位，则以body为准

# pageYOffset

#### Window.pageYOffset:可以获取整个页面往上进去了多少，这个就是用在整个页面，上面那个scorllTop用在元素里面，当元素里面比如有个overflow：auto把它弄出一个滚动条时候就用那个scorllTop

#### Window.pageXOffset: 可以获取整个页面往左进去了多少





# offset

#### offsetParent:指的是拿到该元素带有定位的父级元素，如果父级元素没有定位则返回body

#### offsetWidth：可以获取一个元素的大小，包括边框大小和padding，不包括margin值，也就是width=boder+padding，只读属性不可修改

#### offsetHeight：可以获取一个元素的大小，包括边框大小和padding，不包括margin值，也就是Height=boder+padding



#### offsetTop: 可以获取一个元素距离顶部剩余多少




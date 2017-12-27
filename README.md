# our-training
our training information

##### 1、[搭建SSM工程过程](https://github.com/xcoding-team/our-training/blob/master/%E6%90%AD%E5%BB%BASSM%E5%B7%A5%E7%A8%8B%E8%BF%87%E7%A8%8B.pdf)   
##### 2、[集成SpringMVC+Swagger](https://github.com/xcoding-team/our-training/blob/master/%E9%9B%86%E6%88%90SpringMVC%2BSwagger.pdf)    
##### 3、[vuex详解](https://github.com/xcoding-team/our-training/blob/master/vuex%E8%AF%A6%E8%A7%A3.pdf)    
##### 4、[webpack2](https://github.com/xcoding-team/our-training/blob/master/webpack2.pdf)
##### 5、[git培训](https://github.com/xcoding-team/our-training/blob/master/git%E5%9F%B9%E8%AE%AD.pdf)
##### 6、[【Java基础】多态、static和final关键字](https://github.com/xcoding-team/our-training/blob/master/%E3%80%90Java%E5%9F%BA%E7%A1%80%E3%80%91%E5%A4%9A%E6%80%81%E3%80%81static%E5%92%8Cfinal%E5%85%B3%E9%94%AE%E5%AD%97.pdf)
##### 7、[【Java基础】ArrayList](https://github.com/xcoding-team/our-training/blob/master/%E3%80%90Java%E5%9F%BA%E7%A1%80%E3%80%91ArrayList.pdf)
##### 8、[【Java基础】LinkedList](https://github.com/xcoding-team/our-training/blob/master/%E3%80%90Java%E5%9F%BA%E7%A1%80%E3%80%91LinkedList.pdf)
##### 9、[【Java基础】ArrayList、LinkedList异同](https://github.com/xcoding-team/our-training/blob/master/%E3%80%90Java%E5%9F%BA%E7%A1%80%E3%80%91ArrayList%E3%80%81LinkedList%E5%BC%82%E5%90%8C.pdf)
##### 10、[【Java基础】hashCode、equals详解](https://github.com/xcoding-team/our-training/blob/master/%E3%80%90Java%E5%9F%BA%E7%A1%80%E3%80%91hashCode%E3%80%81equals%E8%AF%A6%E8%A7%A3.pdf)
##### 11、[【Java基础】多线程](https://github.com/xcoding-team/our-training/blob/master/%E3%80%90Java%E5%9F%BA%E7%A1%80%E3%80%91%E5%A4%9A%E7%BA%BF%E7%A8%8B.pdf)
##### 12、[【Java基础】异常](https://github.com/xcoding-team/our-training/blob/master/%E3%80%90Java%E5%9F%BA%E7%A1%80%E3%80%91%E5%BC%82%E5%B8%B8.pdf)
##### 13、[【你不懂JS】作用域与闭包](https://github.com/xcoding-team/our-training/blob/master/%E3%80%90%E4%BD%A0%E4%B8%8D%E6%87%82JS%E3%80%91%E4%BD%9C%E7%94%A8%E5%9F%9F%E4%B8%8E%E9%97%AD%E5%8C%85.png)
##### 14、[【你不懂JS】this](https://github.com/xcoding-team/our-training/blob/master/%E3%80%90%E4%BD%A0%E4%B8%8D%E6%87%82JS%E3%80%91this.pdf)
##### 15、[vue](https://github.com/xcoding-team/our-training/blob/master/vue.pdf)




### 【tips】：    
##### 【Java基础：线程】【遗留问题】：    




##### 【Java基础：异常】【遗留问题】：    




##### 【Java基础：ArrayList】【遗留问题】：    
1、ArrayList 扩容问题；1.5倍 ==》http://baijiahao.baidu.com/s?id=1576524238817524539&wfr=spider&for=pc    
2、ArrayList 不能add基础类型==>自动装箱拆箱(int->Integer...)    
3、HashCode值相同==>http://blog.csdn.net/hl_java/article/details/71511815    

##### 【你不懂JS：this】【遗留问题】：    
1、strict模式===》禁止this关键字指向全局对象

2、arguments    
  ● 每个函数都有一个arguments属性，表示函数的实参集合，这里的实参是重点，就是执行函数时实际传入的参数的集合。    
  ● arguments不是数组而是一个对象，但它和数组很相似，所以通常称为类数组对象，以后看到类数组其实就表示arguments。    
  ● arguments有length属性，可以用arguments[length]显示调用    

3、call、apply、bind    
  ● apply 、 call 、bind 三者都是用来改变函数的this对象的指向的；    
  ● apply 、 call 、bind 三者第一个参数都是this要指向的对象，也就是想指定的上下文；    
  ● apply 、 call 、bind 三者都可以利用后续参数传参；    
  ● bind 是返回对应函数，便于稍后调用；apply 、call 则是立即调用 。    

4、forEach源码==》还是用了call()函数

5、箭头函数：引入箭头函数有两个方面的作用：更简短的函数并且不绑定this。

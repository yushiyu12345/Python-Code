# yield

我们把数据看作是一个容器，在使用数据时，有时候是顺序访问，逐个获取其中的元素，这个过程叫[迭代]

可以在一下几种情况使用yield：

1、调用函数的结果时，需要用 for .. in ..形式，也就是把它看成一个生成器的时候

2、当函数中每次生成的值不一样时，之前我们会使用一个变量来存储，最后一起返回，这时候使用field就可以不需要新变量，直接使用一个生成器
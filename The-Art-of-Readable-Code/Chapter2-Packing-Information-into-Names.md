# Chapter 2: Packing information into names
## Key idea 1: Pack information into your names
一个良好的命名就像一段简短的注释，它能清晰的表达一个变量或者一个方法的含义。然而在实际情况中命名并不是一件容易的事，很多的命名要么没有实际意义，要么含义模糊，不够明确。
## Choose specific words
正如用外语和别人交谈一样，即使发音不太标准，但只要用词准确，听的人也一样能听明白。而如果用词不当，哪怕发音再标准，听的人也可能会一头雾水。所以选择明确的用词对于命名是很重要的，反之，则可能会让阅读代码的人产生困惑，例如：
```js
function getPage(url) {
    // ...
}
```
在上面的例子中，`get` 是一个非常宽泛的词，`getPage` 并不能明确的表达这个方法的用途，它有可能是从缓存或数据库中获取页面，也有可能从网络中抓取。如果是从网络中抓取页面，那么 `fetchPage` 或者 `downloadPage` 可能更好。
## Finding more “Colorful” words
在写作中，普通的文章和优秀的文章的差别也体现在选词上，普通的文章可能用了很多平白无奇的词汇，或者一个词反复用了很多次，而优秀的文章相比而言则可能是词藻华丽。同样的，在命名的时候，也不要千篇一律的用同一个词，换一个词可能会更准确的表达你的意图。下面就是一些例子：

| Word | Alternatives |
| ---- | ------------ |
| send | deliver, dispatch, announce, distribute, route |
| find | search, extract, locate, recover |
| start | launch, create, begin, open |
| make | create, set up, build, generate, compose, add, new |

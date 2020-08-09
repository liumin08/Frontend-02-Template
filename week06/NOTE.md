为什么 first-letter 可以设置 float 之类的，而 first-line 不行呢？
伪元素不能自身作为容器，只能附加到块级元素。first-line是排版之后的line,如果能设置float,display:block等属性，会影响文档流的排版
# html
前端自己的一些总结

#对css中list-style-image的总结：
在ul li中使用自定义的图片作为圆点的展示，去掉list-style-image属性.

<code>list-style-type:none;background:url("ui.png") no-repeat 0rem 0.3rem;</code>
然后设置background-size就可以了
<code>background-size:0.8rem 0.8rem;</code>




节点对象类型：


**DOCUMENT_NODE** (如window.document)

**ELEMENT_NODE** (如body,a,p,script,style,html,h标签)


**ATTRIBUTE_NODE** (如class="funEdges")


**TEXT_NODE** (如HTML文档中由换行符与空白符构成的文本字符)


典型DOM树里的每个节点对象都从Node继承属性和方法

用JavaScript的两个方法以编程的方式创建Element与Text节点

**createElement()、createTextNode()**

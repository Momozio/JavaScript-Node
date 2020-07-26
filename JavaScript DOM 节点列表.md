# JavaScript DOM 节点列表

### Nodelist 获取方法：
1.childNode属性返回Nodelist对象
2.querySelectorAll()方法返回所有的Nodelist对象
3.通过索引来获取（下标）

### HTMLCollection对象的获取：
通过Name、id、TagName、索引 来获取


### HTMLCollection 与 NodeList 的区别
>HTMLCollection 是 HTML 元素的集合。
NodeList 是一个文档节点的集合。
NodeList 与 HTMLCollection 有很多类似的地方。
NodeList 与 HTMLCollection 都与数组对象有点类似，可以使用索引 (0, 1, 2, 3, 4, ...) 来获取元素。
NodeList 与 HTMLCollection 都有 length 属性。
HTMLCollection 元素可以通过 name，id 或索引来获取。
NodeList 只能通过索引来获取。
只有 NodeList 对象有包含属性节点和文本节点。
在使用lodash.js时，经常会看到方法前面有一个下划线（_），这是因为lodash.js库的设计理念是将所有的实用函数（utility functions）都放在一个全局对象中。这个全局对象通常被命名为`_`，并且可以被视为lodash的主要命名空间。

在lodash.js中，使用下划线（_）作为一个简短的变量名是为了减少代码量，让用户更方便地调用库中的方法。它没有特别的语义含义，并且可以根据用户的喜好进行更改。

在使用lodash.js之前，需要确保已引入相应的lodash库文件。在前端项目中，可以通过链接外部脚本（CDN或本地文件）导入lodash.js，或者使用模块化系统（如ES6模块、CommonJS、AMD）导入lodash库。

以下是一个使用lodash.js的应用示例：

```html
<script src="https://cdn.jsdelivr.net/lodash/4.17.15/lodash.min.js"></script>
<script>
  // 使用lodash库中的chunk方法
  const array = [1, 2, 3, 4, 5];
  const chunks = _.chunk(array, 2);
  console.log(chunks);  // Output: [[1, 2], [3, 4], [5]]
</script>
```

在上述示例中，`_.chunk`表示调用lodash库中的`chunk`方法，由于lodash的主要命名空间是`_`，因此我们通过`_`来访问lodash的方法。

希望这个解释对你有所帮助！如果还有其他问题，请随时提问。

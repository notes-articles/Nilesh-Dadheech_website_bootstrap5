

视频地址：

https://www.youtube.com/watch?v=nxO4kekHtMk&list=PLPS6AkdhkIeS37fZWkOsIffodzUrx11Wr&index=1





bootstrap.bundle.min.js

```js
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
```

这个文件是 Bootstrap 的捆绑版本，包含了 Bootstrap 的所有 JavaScript 插件和 Popper.js。

适合希望在一个文件中加载所有 Bootstrap 相关功能的情况，简化了文件管理。



单独加载 Popper.js 和 bootstrap.min.js

```js
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js" integrity="sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.min.js" integrity="sha384-0pUGZvbkm6XF6gxjEnlmuGrJXVbNuzT9qBBavbLwCsOGabYfZo0T0to5eqruptLy" crossorigin="anonymous"></script>
```

`popper.min.js`：这是 Popper.js 的独立文件，主要用于处理工具提示（tooltips）和弹出框（popovers）。

`bootstrap.min.js`：这是不包含 Popper.js 的 Bootstrap JavaScript 插件文件。

适合希望精细控制加载哪些插件的情况。例如，如果你只需要 Bootstrap 的部分功能，或者已经通过其他方式加载了 Popper.js。
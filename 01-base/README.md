# 官方文档
https://vitejs.cn/vite3-cn/guide/why.html

> 官方文档提供的其实是一个脚手架，区别于Vite本身
> 示例是一个vue+ts+vite的预设

## index.html

```
Vite 将 index.html 视为源码和模块图的一部分。Vite 解析 <script type="module" src="..."> ，这个标签指向你的 JavaScript 源码。甚至内联引入 JavaScript 的 <script type="module"> 和引用 CSS 的 <link href> 也能利用 Vite 特有的功能被解析。另外，index.html 中的 URL 将被自动转换，因此不再需要 %PUBLIC_URL% 占位符了。
```
* Vite的入口是index.html，通过 \<script type="module">指向模块

* Vite也支持多个.html作为入口的多页面模式
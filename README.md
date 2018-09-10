# My Awesome Book

This file file serves as your book's preface, a great place to describe your book's content and ideas.

## baseUrl

* Type:`string`

* Default:`'/'`

  部署应用时的基本 URL。用法和 webpack 本身的`output.publicPath`一致，但是 Vue CLI 在一些其他地方也需要用到这个值，所以**请始终使用**`baseUrl`**而不要直接修改 webpack 的**`output.publicPath`。

  默认情况下，Vue CLI 会假设你的应用是被部署在一个域名的根路径上，例如`https://www.my-app.com/`。如果应用被部署在一个子路径上，你就需要用这个选项指定这个子路径。例如，如果你的应用被部署在`https://www.my-app.com/my-app/`，则设置`baseUrl`为`/my-app/`。

  这个值也可以被设置为空字符串 \(`''`\) 或是相对路径 \(`'./'`\)，这样所有的资源都会被链接为相对路径，这样打出来的包可以被部署在任意路径，也可以用在类似 Cordova hybrid 应用的文件系统中。

![](/assets/import.png)


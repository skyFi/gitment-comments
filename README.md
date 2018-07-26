# gitment-comments
存储 https://skyfi.github.io/ 评论系统的评论内容


## 代码实例：

```html
<link rel="stylesheet" href="https://imsun.github.io/gitment/style/default.css">
<script src="https://imsun.github.io/gitment/dist/gitment.browser.js"></script>

<div id="gitment-container"></div>
<script>
    const gitment = new Gitment({
      id: 'id', // 可不填写，默认取评论页地址
      owner: 'skyFi',
      repo: 'gitment-comments',
      oauth: {
        client_id: '***',
        client_secret: '***',
      },
    });
    gitment.render('gitment-container');
</script>
```

## getMDtoShow

你是否饱受 HTML 复杂语法的困扰？

那么这个项目就是为你而生的！

自动获取与当前目录对应的 MD 文件，并转换为 HTML，显示在指定的区域！

### 如何使用

1. 引用 marked：
   ```html
   <script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>
   ```
2. 引用你配置好的 getMDtoShow：
   ```html
   <script src="/gmd2s.js"></script>
   ```
3. 开始撰写 Markdown 吧！

### 配置指南

只有一个配置项：`dir`。

该项填入的是 MD 文件的存放路径，**注意最后不加斜杠**。

For example：如果存在站点根目录，那么就什么都不填；如果存在站点的 `blog` 目录下，就填入 `/blog`。
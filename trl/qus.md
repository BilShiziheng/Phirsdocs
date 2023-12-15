## Q/A大全

### 1.如何开启实时准度？

Phira**主界面**，**设置**，其它，显示实时准度，**开**

### 2.Phira判定多少?还是±80ms吗?

个人感觉比**Phigros**稍微**宽松**一点，大概**82.5ms**，iOS设备的**Late**判定会松一丢丢（相对安卓设备来言）

### 3.你跟群主啥关系

#### 很正常的朋友关系（恼）

### 4.你写这些累不累

还行，在医院写的，只不过这破电脑卡的~~我一秒钟也不想要了~~我很无语，整这玩意我新电脑也就12分钟顶多，这
玩意光`npm -i docsify-cli -g`就花了我22min（恼）
~~这傻逼Github一会行tm一会不行~~
这是部分**代码**
`
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Phira皮肤/自制谱导入教程</title>
  <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
  <meta name="description" content="Description">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0">
  <link rel="stylesheet" href="//cdn.jsdelivr.net/npm/docsify@4/lib/themes/vue.css">
</head>
<body>
  <div id="app"></div>
  <script>
    window.$docsify = {
      name: '',
      repo: ''
    }
  </script>
<script>
    window.$docsify = {
      name: 'Phira皮肤/自制谱导入教程',
      repo: 'https://github.com/BilShiziheng/Phirsdocs',
      loadNavbar: true,
      loadSidebar: true, // 加载自定义侧边栏
      maxLevel: 2, // 默认情况下会抓取文档中所有标题渲染成目录，可配置最大支持渲染的标题层级。
      subMaxLevel: 4, // 生成目录的最大层级
      mergeNavbar: true, // 小屏设备下合并导航栏到侧边栏
      alias: { // 定义路由别名，可以更自由的定义路由规则。 支持正则
        '/.*/_sidebar.md': '/_sidebar.md',//防止意外回退
        '/.*/_navbar.md': '/_navbar.md'
      }
    }
  </script>
  <!-- Docsify v4 -->
  <script src="//cdn.jsdelivr.net/npm/docsify@4"></script>
</body>
</html>
`

### 5.多久更新一次？

尽量**紧随Phira的更新**而更新


这个文档（奇奇怪怪的问题）不一定

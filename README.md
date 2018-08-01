# myajax
一个简单的前端ajax模版引擎插件
## 需要：
1. jquery
2. handlebar.js
## 使用：
      引入jquery、handlebar.js、myajax.js以及config文件
### 目标容器：

    <div class="ajax-box" ajax-id="1"></div>
### tpl：

    <script class="ajax-tpl" ajax-id="1" type="text/x-handlebars-template"></script>
### js：

    var myajax = new Ajaxer({
    main: function () {
        this.rander();
    },
    url: "#",
    ajaxid: [1],
    after: function () {
    }
		});
## 插件内含图片自适应插件：
# imgautosize
## 使用：
		myajax.js
### img：
		<img class="autosize">
### js：
		var imgsize = new imgAutoSize();

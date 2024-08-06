# Better_Alist  

* 半透明化目录背景  
* 随机旅行背景图  
* 添加回到顶部猫猫  

## 使用方法  
   * 以下内容针对静态背景，视频背景详见[此处](https://github.com/TheSmallHanCat/Better_Alist/issues/7)
   * 在Alist后台页面依次选择```设置```-->```全局```
   * 将以下内容添加到对应框框内
     * 自定义头部  
        ```html
        <link href="https://cdn.jsdelivr.net/gh/susetao/Better_Alist@main/alist.css" rel="stylesheet" type="text/css">  
        ```  

     * 自定义内容  

        ```html
        <script src="https://cdn.jsdelivr.net/gh/susetao/Better_Alist@main/jq.js"></script>
        <div class="st-Container">
            <a style='display:none' class="st-Menu closed" id="st-Menu" href="javascript:void(0);"></a>
        </div>
        <div class="sw-Hennnyano" id="sw-Hennnyano">
            <div class="layer body w100" data-depth="0.1"></div>
            <div class="layer eyes w100" data-depth="0.2"></div>
        </div>
        <script src="https://cdn.jsdelivr.net/gh/susetao/Better_Alist@main/js/lib.js"></script>
        <script src="https://cdn.jsdelivr.net/gh/susetao/Better_Alist@main/js/parallax.min.js"></script>
        <script src="https://cdn.jsdelivr.net/gh/susetao/Better_Alist@main/js/app.bundle.js"></script>
        <div id="jsi-flying-fish-container" class="fish-container"></div>
        <script src='https://cdn.jsdelivr.net/gh/susetao/Better_Alist@main/fish.js'></script>
        ```
# 个人博客自用


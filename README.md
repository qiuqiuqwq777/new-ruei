# new-ruei
这是SL/秘密实验室 Exiled插件lab也可以调用
这是根据lab ruei制作的exiled插件

用法和lab ruei的一样 

new ruei可以和HintServiceMeow插件兼容

## 使用方法

using ruei_exiled.hint;

这是个示例

显示"欢迎" 5秒

var display = HintManager.Get(player);

display.Show(new HintTag("a"), new TextHint(700, "欢迎"), 5f);

其他方法

new DynamicHint 方法

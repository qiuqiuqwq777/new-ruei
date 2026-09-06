# new-ruei
这是根据lab ruei制作的exiled插件\n
用法和lab ruei的一样 \n
new ruei可以和HintServiceMeow插件兼容\n
## 使用方法\n
using ruei_exiled.hint;\n
这是个示例\n
// 显示"欢迎" 5秒\n
var display = HintManager.Get(player);\n
display.Show(new HintTag("a"), new TextHint(700, "欢迎"), 5f);\n
其他方法\n
new DynamicHint 方法

# new-ruei
这是SL/秘密实验室 Exiled插件lab也可以调用
这是根据lab ruei制作的exiled插件

用法和lab ruei的一样 

new ruei可以和HintServiceMeow插件兼容

## 使用方法

使用前需要加入引用才可以使用

这是个示例

显示5秒
using RueDisplay = ruei_exiled.hint.PlayerDisplay; 

using BasicElement = ruei_exiled.hint.TextHint;

using Tag = ruei_exiled.hint.HintTag;

      var display = RueDisplay.Get(p);
      
      display?.Show(new Tag("a"),
      
          new BasicElement(800, "12345678790"),
          
          5f);

其他方法

new DynamicHint 动态显示

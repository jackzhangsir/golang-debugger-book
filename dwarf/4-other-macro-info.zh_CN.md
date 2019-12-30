### 5.4.2 宏信息

大多数调试器很难显示和调试具有宏的代码。 用户看到带有宏的原始源文件，而代码则对应于宏展开后的内容。

DWARF调试信息中包含了程序中定义的宏的描述。 这是非常基本的信息，但是调试器可以使用它来显示宏的值或将宏翻译成相应的源语言。

c\c++等需要支持宏的编程语言中需要用到这里的信息.debug_macro，go语言中用不到，这里就不展开了。

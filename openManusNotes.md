### convetions
`__versioin__` 有助于客户检查版本信息

`__all__` 用于当使用from module import * 时,哪些名称会被导入.如果没有此属性,默认会导入所有不以下划线开头的名称.库开发时添加__all__更加规范 安全.

`_ClassNameXXX` 以_开头的类,函数代表内部实现或者私有,不建议外部使用.但是实际不强制限制外部使用. 


### keywords 
##### `async`



##### `await`


### annotations
##### `@classmethod` 
 python 内置装饰器decorator，类方法.通常第一个参数为cls为类本身.操作的是类对象而不是实例对象.k可以通过类本身和其实例来调用
##### 
# author:zhongzhaocong

# 什么是magic number
> magic number特指代表特定含义的代码中的数字。消除magic number的目的，在于提高代码的可维护性，消除令人费解的代码含义。


而目前做的工作，只是把`数字和文字互转的辅助对象合到一起`了。剩下的工作没有帮用户解决。

# 为什么使用label-array
label-array 的主要作用是`聚合`数字和文字互转时用到的`辅助对象`。和另外的`别名系统`结合起来，可以有效管理和消除magic number的使用。
> 别名系统不一定在业务场景中需要一起被使用到。

labelArray 的可选功能就是别名系统。只要同时填入alias就能帮助生成别名辅助对象，用以以别名替换代码中数字。





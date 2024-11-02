# 炉石兄弟策略的编译


# 炉石兄弟策略的编译

1. 删除 `CompiledAssemblies` 文件夹中的`DefaultRoutine.dll`文件，重新打开主程序时会自动对`Routines\DefaultRoutine`中的策略进行编译，重新生成`DefaultRoutine.dll`
2. 使用VisualStudio进行编译，在VisualStudio中创建项目，将`Bots` `Routines`文件夹包含进来，**项目属性 →应用程序→输出类型→类库** ，在菜单栏的生成→生成解决方案，即可生成.dll 文件，可以手动重命名为`DefaultRoutine.dll`，也可在**项目属性 →应用程序**中，将程序集名称设置为`DefaultRoutine`，编译完成后手动将.dll文件复制到兄弟主程序的`CompiledAssemblies` 文件夹中。



---

> 作者: Caaat  
> URL: https://icy-cat.github.io/posts/3fdce8e/  


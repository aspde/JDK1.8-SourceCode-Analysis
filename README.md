源码版本：jdk-8u333  

包含以下八个包
1. io
2. lang
3. math
4. net
5. nio
6. text
7. time
8. util  

环境配置
1. Jdk环境，Maven环境
2. 破坏双亲委派机制：Run -> Edit Configurations -> Modify Options -> Add VM Options ->  
例：-Xbootclasspath/p:"F:\projects\JDK1.8-SourceCode-Analysis\target\classes"
3. 自由添加注释不影响调试：File -> Project Structure -> SDKs -> SourcePath -> 添加文件路径在最上面，  
例：F:\projects\JDK1.8-SourceCode-Analysis\src\main\java，其他可以删了重建
4. 消除错误和警告：File -> Project Structure -> Project -> Language Level（设置10-Local variable type inference），  
解决JapaneseDate类的错误

参考链接：[曹工力荐：调试 jdk 中 rt.jar 包部分的源码（可自由增加注释，修改代码并debug）](https://www.cnblogs.com/grey-wolf/p/12817615.html)

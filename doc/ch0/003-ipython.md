## IPython

**命令**

命令 | 说明
----|---------
`?`                  |  IPython 特征说明
`%quickref`          |  IPython 使用手册
`help`               |  内置帮助函数
`object? / object??` |  获取object信息


#### magic函数

 - 操作代码
 - 控制IPython
 - 其它

```shell
# 在IPython中执行
%lsmagic # 获取magic函数列表

import json

%pfile json
%pdoc json.loads
%pinfo json.loads
```

命令 | 说明
----|-----
%load          | 导入外部文件并执行
%save          | 将IPython的代码保存
%rerun 5-7     | 重新执行6-7行
Ctrl+r         | 反向查找
Ctrl+p, Ctrl+n | 输入查找

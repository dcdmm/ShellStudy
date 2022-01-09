### 构建基本脚本

```shell
#!/bin/bash 
# 文件的第一行指定要使用的shell
  
echo "hello shell"  # 井号(#)后为注释

```

### 脚本的执行

```markdown
[root@localhost test.]# cat a.sh
#!/bin/bash

echo "hello shell"
[root@localhost test.]# sh a.sh   # 执行方式一
hello shell
[root@localhost test.]# ./a.sh
-bash: ./a.sh: Permission denied
[root@localhost test.]# chmod u+x a.sh			# 增加执行权限
[root@localhost test.]# ./a.sh		# 执行方式二
hello shell
[root@localhost test.]# 
```


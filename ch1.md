pytest

参数`-v`可以打印详细的出错信息，包括指出错误位置
eg:
```py3
$ pytest -v test_two.py
```

fixture(用于存放相同的启动逻辑和销毁逻辑)

可以使用`pytest --help`查看所有的命令和选项参数

如果直接使用命令`pytest`不加任何参数，pytest会递归遍历每个目录及其子目录，运行所有测试。











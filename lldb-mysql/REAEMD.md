# 熟练使用 LLDB 调试 MySQL 代码
https://www.bilibili.com/video/BV1B64y1c7Fx


Fine mysql processid
```
ps -ef | grep mysql   
```

lldb

(lldb) process attach --pid <pid>

(lldb) process continue


Set breakpoint on method
```
(lldb) breakpoint set --name my_sql_alter_table
```

```
(lldb) breakpoint list

(lldb) step

```



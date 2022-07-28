```
  gdb demo1.exe

  (gdb) list              # show source code, 10 lines

  (gdb) b main            # break
  (gdb) b demo1.cpp:8     # break at line 8
  (gdb) i b               # list all breakpoints
  (gdb) r                 # run
  (gdb) n                 # next
  (gdb) p <variable>      # print
  (gdb) i locals          # print all local variables
  (gdb) c                 # run and stop at next breakpoint
```
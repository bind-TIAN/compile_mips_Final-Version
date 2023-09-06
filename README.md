# compile_mips
---
## 写在前面
---
本项目基于之前的github项目设计并实现了`MIPS`版本的编译器，在编译器构建上的细节这里不再过多阐述，如有需要请移步至[该处](https://github.com/bind-TIAN/compile_Alpha-Version)

## 创新点呈现
---
*    在适合PASCAL语言的代码架构上，通过处理符合C0文法的语言代码，实现了`MIPS语句`的实时打印和输出，并且其生成的MIPS程序可以在`Mars`软件上运行，输出结果。
*    构建了一套`端到端`的设计理念：即从`类C语言代码`，编译成`MIPS`程序并在`Mars解释程序`中解释执行。

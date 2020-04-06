# 欢迎来到ucore step-by-step的世界

*step by step, to the light of u*   ----[《Good Night》](https://music.163.com/#/song?id=1421195795)

你好，冒险者。让我们一起进入ucore的内部，一步一步构建自己的操作系统！

写一个操作系统难吗？别被现在上百万行的Linux和Windows操作系统吓倒。当年Thompson乘他老婆带着小孩度假留他一人在家时，写了UNIX；当年Linus还是一个21岁大学生时完成了Linux雏形。站在这些巨人的肩膀上，我们能否也尝试一下做“巨人”的滋味呢？

MIT的Frans Kaashoek等在2006年参考PDP-11上的UNIX Version 6写了一个可在X86上跑的操作系统xv6（基于MIT License），用于学生学习操作系统。我们可以站在他们的肩膀上，基于xv6的设计，尝试着一步一步完成一个从“空空如也”到“五脏俱全”的“麻雀”操作系统—ucore，此“麻雀”包含虚存管理、进程管理、处理器调度、同步互斥、进程间通信、文件系统等主要内核功能，总的内核代码量（C+asm）不会超过5K行。充分体现了“小而全”的指导思想。

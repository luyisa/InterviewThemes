1. 什么是Goroutine？与线程的区别？<br/>
```
Goroutine是go GMP模式下多线程高并发的轻量级执行线程，goroutine创建和销毁的成本小于线程，且不需要和操作系统打交道，由go runtime来负责和系统交互，goroutine的调度方式是协作式的，线程是系统级别的，调度方式是抢占式的，goroutine的切换开销也比线程小
```
2. 什么是Channel？作用是什么？<br/>
```
channel是通道，是用来原子性数据交换的，它是个FIFO的策略，避免进程间共享内存通信
```
3. 什么是Slice？与数组的区别。<br/>
```
slice是切片，是个结构体，里面包含数组、长度以及容量
```
4. 什么是Map？创建和删除Map？如何在Map中删除键值对？<br/
```

```
6. 什么是Interface？<br/>
7. Defer语句的作用（执行顺序LIFO）<br/>
8. Go的垃圾回收机制？ <br/>
```
尽可能使用栈而不是堆，通过使用值类型和指针类型的区别来避免在堆上分配内存
使用对象池来重复利用对象，避免重复创建和销毁对象的开销
使用标准库提供的内存池，如sync.Pool
```
8. Context的作用<br/>
9. Go中的错误Error？自定义实现error接口来创建自定义错误<br/>
10. Reflection的作用，如何使用反射操作变量和类型？<br/>
11. Golang中的函数是第一类值（First Class Value）？<br/>
12. 并发安全concurrent safe<br/>
13. 包管理和依赖管理有哪些工具？<br/>
14. Golang中的递归函数？<br/>
15. Golang中的闭包？如何使用闭包？<br/>
16. Golang中的HTTP服务器？<br/>
17. struct{}的用途

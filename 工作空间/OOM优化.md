
### Oom

OOM就是所谓的内存溢出（Out Of Memory），也就是说内存占有量超过了VM所分配的最大

### 出现OOM的原因

1. 加载对象过大
2. 相应资源过多，来不及释放

### 如何解决

1. 在内存引用上做些处理，常用的有软引用、强化引用、弱引用
2. 在内存中加载图片时直接在内存中作处理，如边界压缩
3. 动态回收内存
4. 优化Dalvik虚拟机的堆内存分配	
5. 自定义堆内存大小
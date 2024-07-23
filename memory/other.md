# memory

其他功能

** 代码示例：**
```features
memory.handle_to_ptr(int entity)
```

**表成员：**
```lua
pointer handle_to_ptr(int entity) -- 返回存储句柄的内存地址，返回类型为pointer类，参数填写为实体句柄，获取方法如下
local veh = OBJECT.CREATE_VEHICLE(具体参数请参照native方法)

int ptr_to_handle(pointer ptr) - 返回内存地址中存储的实体句柄

pointer allocate(int size) - 创建一片内存空间，参数填写需要创建的大小，返回pointer类

void free(pointer ptr) - 释放创建的内存空间，参数填写创建的内存地址
```

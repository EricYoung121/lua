# locals

**使用方法**

```features
locals.set_int("脚本名称", 脚本索引) 

```

**表成员**
```lua

int get_int(const std::string& script, int index)  - 取整数型
std::uint32_t get_uint(const std::string& script, int index)  - 取正整数型
float get_float(const std::string& script, float index)   - 取单浮点（小数型）

void set_int(const std::string& script, int index, int val)  - 取单浮点（小数型）

memory::pointer get_pointer(const std::string& script, int index)   - 取全局变量的地址

```

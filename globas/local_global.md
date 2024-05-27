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
Vector3 get_vec3(const std::string& script, int index) - 取结构体，详情参考vector.md文件

void set_int(const std::string& script, int index, int val)  - 写整数
void set_uint(const std::string& script, int index, std::uint32_t val)  - 写无符号数
void set_float(const std::string& script, int index, float val)  - 写单浮点（小数型）
void set_vec3(const std::string& script, int index, vector3 val)  - 写结构体

memory::pointer get_pointer(const std::string& script, int index)   - 取全局变量的地址

```

# globals


**script_global**
```lua

int get_int(int global)  - 取整数型

int get_uint(int global)   - 取正整数型

float get_float(int global)  - 取单浮点（小数型）

std::string get_string(int global)   - 取字符串

void set_int(int global, int val)   - 写整数型

void set_uint(int global, unsigned int val)   - 写正整数型

void set_float(int global, float val)   - 写单浮点（小数型）

void set_string(int global, const std::string& str, int max_length)    - 写字符串

memory::pointer get_pointer(int global)   - 取全局变量的地址

```

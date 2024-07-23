# memory

内存操作

** 代码示例：**
```features
local addr = memory.scan("定位地址名称", "66 0F 6E 0D ? ? ? ? 0F B7 3D"):add(1):sub(1):rip():deref():get_address()
```

**表成员：**
```lua
pointer scan(const std::string& name, const std::string& pattern) - 根据sig定位内存地址

**pointer类成员**

pointer add(std::uint64_t offset) - 定位后的地址加偏移

pointer sub(std::uint64_t offset) - 定位后的地址减去偏移

pointer rip() - 读定位的地址偏移后 + 0x4

std::string get_string()  - 读定位后的地址字符串

std::string set_string(const std::string& string, int max_length) - 写内存字符串，参数一为内容，参数二为字符串长度

bool is_null() - 地址是否为nullptr

pointer deref() - 读定位后地址长整数型，对定位地址偏移操作，不返回长整数地址

bool is_valid() - 地址是否有效

std::uintptr get_address() - 返回定位的地址，返回类型为pointer类，后面可以使用pointer类方法
例子：
memory.scan("定位地址名称", "66 0F 6E 0D ? ? ? ? 0F B7 3D"):get_address():is_null()


std::uint8_t get_byte() - 在语法结尾，读最无符号字节型

std::uint16_t get_short() - 在语法结尾，读地址无符号短整数

std::uint32_t get_int() - 在语法结尾，读地址字无符号整数

std::uint64_t get_long() -  在语法结尾，读地址字无符号长整数

float get_float() - 在语法结尾，读地址字单浮点（小数型）

void set_byte(std::uint8_t value) - 在语法结尾，写地址无符号字节型

void set_short(std::uint16_t value) - 在语法结尾，写地址无符号短整数

void set_int(std::uint32_t value) - 在语法结尾，写地址字无符号整数

void set_long(std::uint64_t value) -  在语法结尾，写地址字无符号长整数

void set_float(float value) - 在语法结尾，写地址小数型

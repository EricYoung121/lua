# memory

内存操作

** 代码示例：**
```features
local addr = memory.scan("定位地址名称", "66 0F 6E 0D ? ? ? ? 0F B7 3D"):add(1):sub(1):rip():get_address()
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

bool is_null() - 地址是否为0

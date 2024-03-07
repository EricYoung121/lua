# slider_int

弹出菜单的提示框

**代码示例:**
```lua
local val = 0
gui.add_tab("添加一个选项"):add_tab("添加一个子选项"):slider_int("添加一个整数滑块条", "滑块条的提示", val, 0, 100)

local val = 0
gui.add_tab("添加一个选项"):slider_int("添加一个整数滑块条", "滑块条的提示", val, 0, 100)

```

组件相关函数

## slider_int(std::string name, std::string description, int val, int min, int max)
std::string get_text() -- 取标题 

void set_text(std::string)  -- 置标题 

std::string get_description() -- 取说明 

void get_description(std::string) -- 置说明 

int get_value()  -- 取滑块条位置 

void set_value(int)  -- 设置滑块条位置 

void set_min(int)  -- 设置最小值 

void set_max(int)  -- 设置最大值 

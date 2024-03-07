# slider_int

弹出菜单的提示框

**代码示例:**
```lua
local val = 0
gui.add_tab("添加一个选项"):add_tab("添加一个子选项"):slider_int("添加一个整数滑块条", "滑块条的提示", val, 0, 100)

```

组件相关函数

## gui.slider_int(std::string title, std::string text, std::uint32_t duration)
title 标题   
text 提示内容   
duration 持续时间   

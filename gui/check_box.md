# check_box

用于在菜单中添加选择框组件

**代码示例:**
```lua
local check_box = gui.add_tab("主选项"):add_tab("子选项"):check_box("添加一个选择框", "添加选择框提示", function()

if check_box:is_enabled() then -- 判断是否启动
    -- 这里填写执行的函数代码
end)

gui.add_tab("主选项"):check_box("添加一个选择框", "添加选择框提示", function()

--这里填写执行的函数代码

end)
```

组件相关函数

## gui.add_check_box(std::string name, function)

类成员
```lua
void set_text(std::string)  --设置标题
 
std::string get_text()  --取标题
 
bool is_enabled()  --是否选中

void set_enabled(bool)  --置选中

```

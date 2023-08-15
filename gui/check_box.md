# check_box

用于在菜单中添加选择框组件

**代码示例:**
```lua
gui.check_box("添加一个选择框",function()

--这里填写执行的函数代码

end)
```

组件相关函数

## gui.check_box(std::string name, function)

类成员
```lua
void set_text(std::string)  --设置标题
 
std::string get_text()  --取标题
 
bool is_enabled()  --是否选中

void set_enabled(bool)  --置选中

```

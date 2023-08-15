# add_input_int 
用于在菜单中添加整数型编辑框组件

**代码示例:**
```lua
gui.add_input_int("添加一个整数编辑框",function()

--这里填写执行的函数代码

end)
```


组件相关函数

## gui.add_input_int(std::string name, function)

类成员
```lua
void set_value(int)  --置编辑框内容
 
int get_value()  --取编辑框内容
 
void set_text(std::string)  --置标题

std::string get_text()  --取标题

```

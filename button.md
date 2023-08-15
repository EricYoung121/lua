# button

用于在菜单中添加ui组件

**代码示例:**
```lua
gui.add_button("添加一个按钮",function()

--这里填写执行的函数代码

end)
```

组件相关函数

## gui.add_button(std::string name, function)
**类成员**
```lua
button["baize"] = gui.add_button(std::string name, function)

button["baize"]:set_text(std::string name) -- 设置按钮标题
name = button["baize"]:get_text(std::string name) -- 获取按钮的标题

```

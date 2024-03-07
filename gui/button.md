# button

用于在菜单中添加按钮组件

**代码示例:**
```lua
gui.add_tab("自我选项"):add_tab("子选项"):button("子选项下的按钮", "按钮的提示", function()

-- 填写点击按钮后执行的功能代码

end)

gui.add_tab("一个选项"):button("子选项下的按钮", "按钮的提示", function()

-- 填写点击按钮后执行的功能代码

end)
```

组件相关函数

## gui.button(std::string name, std::string description, function)
**类方法**
```lua
button["baize"]:set_text(std::string name) -- 设置按钮标题
button["baize"]:set_description(std::string name) -- 设置按钮提示
name = button["baize"]:get_text() -- 获取按钮的标题
name = button["baize"]:get_description() -- 获取按钮提示
```

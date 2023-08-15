# script

```lua
void register_looped(const std::string& name, function func) - 注册一个循环 参数1填写名称 参数2填写需要循环执行的函数

void run_in_fiber(function func) - 在光纤池中执行函数

void yield() - 循环空转 释放内存防止游戏卡顿

void sleep(int ms) - 延时
```

# script

**表成员：**
```lua
void register_looped(std::string name, function func)  - 注册循环，将lua函数在循环中运行 参数一为任意与之前注册循环的函数不相同的名称索引，参数二为函数
void run_in_fiber(sol::protected_function func_) - 将函数在纤维池中运行，不会进行循环，也不会影响后续代码执行，类似开辟一条新的线程运行里面的代码，register_looped同理，只是循环执行function
void execute_as_script(const std::string& script_name, sol::protected_function func) - 在指定脚本线程中运行函数，参数一为脚本线程名称，参数二为函数
void yield() - 循环中使用，一个延时时间为0的空延时，用于释放内存
void sleep(int ms) - 循环使用，设定等待事件，延时之后执行后续代码，可用于释放内存
```

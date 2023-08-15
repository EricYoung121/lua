# SYSTEM

系统类native函数

**使用示例：**
```features
SYSTEM.WAIT(ms)
```

**表成员**
```lua
void WAIT(int ms)

int START_NEW_SCRIPT(const char* scriptName, int stackSize)

int START_NEW_SCRIPT_WITH_ARGS(const char* scriptName, Any* args, int argCount, int stackSize)

int START_NEW_SCRIPT_WITH_NAME_HASH(Hash scriptHash, int stackSize)

int START_NEW_SCRIPT_WITH_NAME_HASH_AND_ARGS(Hash scriptHash, Any* args, int argCount, int stackSize)

int TIMERA()

int TIMERB()

void SETTIMERB(int value)

void SETTIMERA(int value)

float TIMESTEP()

float SIN(float value)

float COS(float value)

float SQRT(float value)

float POW(float base, float exponent)

float LOG10(float value)

float VMAG(float x, float y, float z)

float VMAG2(float x, float y, float z)

float VDIST(float x1, float y1, float z1, float x2, float y2, float z2)

float VDIST2(float x1, float y1, float z1, float x2, float y2, float z2)

int SHIFT_LEFT(int value, int bitShift)

int SHIFT_RIGHT(int value, int bitShift)

int FLOOR(float value)

int CEIL(float value)

int ROUND(float value)

float TO_FLOAT(int value)

void SET_THIS_THREAD_PRIORITY(int priority)
``` 

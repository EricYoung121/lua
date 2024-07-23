# network

**表成员：**
```lua
void trigger_script_event(int bitset, sol::table _args)  - 发送网络事件
void give_pickup_rewards(int player, int reward) - 掉落可拾取物品，如钱袋，武器，收藏品等，参数一填写player id，参数二填写凋落物hash
void set_player_coords(int player, float x, float y, float z) - 设置玩家坐标
void set_all_player_coords(float x, float y, float z) - 设置当前战局内所有玩家坐标
```

# entity

实体操作

**表成员：**
```lua
std::vector<Entity> entities.get_all_vehicles_as_handles() - 取载具池中所有载具

static std::vector<Entity> get_all_objects_as_handles() - 取对象池中所有对象

std::vector<Entity> get_all_peds_as_handles() - 取Ped池中所有Ped

bool take_control_of(Entity entity) - 请求控制实体

bool take_control_of_try_count(Entity entity, int try_count) - 多次请求控制，参数2为尝试请求控制次数

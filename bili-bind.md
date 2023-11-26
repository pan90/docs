## B站账号绑定（白名单）
一个游戏角色一个B站账号一对一绑定，只有绑定B站账号才能进服

### 玩家绑定教程
TODO：还没写

### 玩家指令
- `bili-bind player`   查询自己的B站账号
- `bili-bind player [玩家名或UUID]`    查询指定玩家的B站账号
- `bili-bind uid <B站UID>`      根据B站UID查询绑定信息
- `bili-bind code`      生成绑定验证码
- `bili-bind check`     扫描B站的指定视频评论区，查找自己的绑定验证码进行绑定

### 管理员指令
- `bili-bind add <玩家名或UUID> <B站UID>`   为指定玩家添加B站账号绑定
- `bili-bind remove <玩家名或UUID>`     删除指定玩家的B站账号绑定
- `bili-bind bind-code <绑定验证码> <B站UID>`   通过玩家的绑定验证码为玩家添加B站账号绑定
- `bili-bind confirm <确认验证码>`      通过确认验证码为玩家添加B站账号绑定
- `bili-bind reload`        重载配置，清除缓存
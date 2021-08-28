# Ninja
Ninja 仅供学习参考使用，请于下载后的 24 小时内删除，本人不对使用过程中出现的任何问题负责，包括但不限于 `数据丢失` `数据泄露`。
Ninja 仅支持 qinglong 2.9+

## 常用指令

```bash
git clone https://github.com/QiFengg/ninja /ql/ninja
cd /ql/ninja/backend
git checkout
git pull
pnpm install
pm2 start
cp sendNotify.js /ql/scripts/sendNotify.js
```

## 配置文件
`推送二维码请放在 /backend/static 重命名为push.jpg`
``` bash
# 是否允许添加账号 不允许添加时则只允许已有账号登录
ALLOW_ADD=true

#允许添加账号的最大数量
ALLOW_NUM=50

# Ninja 运行端口
NINJA_PORT=5701

# Ninja 是否发送通知
NINJA_NOTIFY=true

# user-agent
NINJA_UA="Mozilla/5.0 (iPhone; U; CPU iPhone OS 4_3_2 like Mac OS X; en-us) AppleWebKit/533.17.9 (KHTML, like Gecko) Version/5.0.2 Mobile/8H7 Safari/6533.18.5 UCBrowser/13.4.2.1122"

# 青龙2.9+ OpenApi 接口参数配置
QL_URL="http://localhost:5700"
QL_Client_ID=
QL_Client_Secret=
```
![](https://i0.hdslb.com/bfs/album/e09373b7579023acc8dc12dc9dab2c6cd497d537.png)
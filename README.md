<a href="https://imgse.com/i/x7dmDJ"><img src="https://s1.ax1x.com/2022/11/01/x7dmDJ.png" alt="x7dmDJ.png" border="0" />

## 📫 Get in Touch

[![BiliBili](https://img.shields.io/badge/-Chisato73-00a1d6?style=flat-square&logo=bilibili&logoColor=fff)](https://space.bilibili.com/323081938)
[![Steam](https://img.shields.io/badge/-ChisatoNishikigi73-000000?style=flat-square&logo=steam&logoColor=white&labelColor=000000)](https://steamcommunity.com/id/12389463925)
![E-Mail](https://img.shields.io/badge/-lxr2061895177@163.com-168de2?style=flat-square&logo=mail.ru&logoColor=white&labelColor=168de2)
### 😄 Welcome to my cafe [@LycoReco-Cafe ｜ LycoReco 咖啡馆](https://github.com/LycoReco-Cafe)

## 当前功能

* 登录
* 战斗
* 好友
* 传送
* 祈愿
* 多人游戏 *部分* 可用
* 从控制台生成魔物
* 物品 (接收或升级角色、武器等)


## 独有功能

- ### 特性
    - **Player_Login_Lua**
        - **介绍:** data->windSeed目录中提供一个名为login.luac的api以供服务器在每个玩家登陆时发送特定命令
        - **风依旧在吹**
    - **跳过开场CG**
        - **介绍:** config->CreateOption 可供跳过cg
        - <details><summary><b> <code>Config<br></code></b></summary><code>SkipOpeningCutscene->是否跳过</code><br><code>CharacterId->默认角色id</code><br><code>AccountNickName->默认用户名（填空则为账号名）</code><br><code>NameCardId->默认名片id</code></details>

- ### 指令
    - **WorldChat** ｜ 跨服务器聊天
        - **介绍:** 跨服务器的聊天方式，可以与各个服务器的玩家聊天「_只用于服务器_」
        - <details><summary><b> <code>用法<br></code></b></summary><code>create [Port] [WorldName（随便填，暂时没用）] [name] ｜ 创建一个去中心服务器</code><br><code>link [linkIp] [linkPort] [Port] [PID] [name] ｜ 连接一个去中心服务器</code><br><code>link config [PID] ｜ 使用config里的配置连接</code><br><code>send [message] ｜ 发送服务器消息</code><br><code>close ｜ 断开连接</code><br><code>set send [times] | 设置玩家一分钟内发送消息的条数</code></details>
    - **Auth** ｜ 玩家身份验证系统
        - **介绍:** 用于验证账号是否属于此玩家，目前仅限制worldChat与使用命令
        - <details><summary><b> <code>用法<br></code></b></summary><code>lp [Password] | 验证密码，初次使用则为设置密码</code><br><code>rp [RawPassword] [Password] | 重置密码，需输入原密码与新密码</code></details>
    - **Secure** ｜ 服务器安全系统
        - **介绍:** 服务器安全策略系统
        - <details><summary><b> <code>用法<br></code></b></summary><code>strategy add/delete [strategy] | 添加/删除安全策略</code></details>
        - <details><summary><b> <code>策略 ｜ DISPATCH_PROTECT<br></code></b></summary><code>DISPATCH_TIME | 限制在单位时间内客户端注册账号个数的策略</code><br><code>DISPATCH_IP_COUNT | 限制单个IP在单位时间内在客户端注册账号个数的策略</code><br><code>DISPATCH_IP_TIME | 限制单个IP在客户端注册账号总数</code></details>




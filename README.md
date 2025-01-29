## FakeLowPlayer
是项目 [FalePlayer](https://github.com/RELAY-CN/FakePlayer) 的低配版本  
用于在 Rusted Warfare 的房间上以最简单的方案创建一个虚假的玩家  

默认方案
> 创建一直在的玩家  

特性  
> 在开始后不能正常游戏, 只能当摆设  
> 不能完整模仿协议, 很容易查出  

**不为此负责**  

## 使用依赖
> RELAY-CN Utils  
> Jetty  

## Tags
`红队` `攻击性`   

## 使用
### 单个玩家
```text
java -jar player.jar ip:port [passwd]
```
例子
```text
java -jar player.jar 1.1.1.1:5123 passwd
```

## 其他
仅供压测

### Licenses  
[RELAY-CN 团队专用软件许可证](https://github.com/RELAY-CN/.github/blob/main/LICENSE.md)

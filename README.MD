# SimpleGroupAuth

简单的进群验证插件 https://mirai.mamoe.net/topic/475/

该插件仍处于开发状态，请等待后续更新

```
/ga-switch 群号 模式序号   ---切换验证模式

0. DISABLED,  不处理
1. ENTERNED_CAPTCHA,  要求进群后的验证码
2. ENTERNED_CHALLENGE,  要求进群后回答问题
3. AUTO_ACCEPT,  自动判断进群答案并接受(未实现)
4. AUTO_ACCEPT_DENY  自动判断进群答案并接受或拒绝(未实现)
```
ENTERNED_CHALLENGE 现已可用，请查看数据目录内的`scripts`文件夹内的文件完成配置

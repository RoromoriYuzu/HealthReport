# HealthReport
青龙企业微信健康打卡脚本

## 环境变量 
`HealthReport` 格式为 HealthReport = wwrtx.xcx.sid&姓名&学号&手机号&省&市&区&详细地址&经度&纬度

多个账号用 @分割
## 定时规则
0 0 0/1 * * ? 
需要一小时运行一次来做到 Cookie 保活，仅在早晨8点或过了8点未填写的情况下填写。

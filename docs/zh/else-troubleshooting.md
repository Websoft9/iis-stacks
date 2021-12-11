# 故障处理

#### 使用 Powershell 运行 `plcncli install sdk` 报错 "The value must be greater than or equal to zero"

错误信息：System.ArgumentOutOfRangeException: The value must be greater than or equal to zero and less than the console's buffer size in that dimension. (Parameter 'top')
Actual value was 50.  

错误原因： 日志信息溢出  

解决方案：plcncli install sdk ...  | Out-Null ，增加一个 Out-Null 参数，即不输出日志。
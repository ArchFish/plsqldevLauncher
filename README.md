plsqldevLauncher
================

一个可以启动plsqldev在不同环境变量的工具，不修改系统

[CTRL]
;多开PLSQL Dev，true 允许

AllowMultiWin = false



;是否使用系统安装的Oracle Client，false 不使用

UseClient = false



;强制按照本ini改写PLSQL Dev的个性配置，true 改写

ForceWrite = false



;启动软件前使用notepad修改TNS，0  不修改 ;1  只在下次; >=2  每次

EditTNS = 0





[CONFIG]
;oci文件所在文件夹，支持相对路径

OCIPath = .\instantclient_11_2



;tnsnames.ora文件所在文件夹，支持相对路径

TNSPath = .\instantclient_11_2\NETWORK\ADMIN



;默认日期格式 YYYY-MM-DD HH24:MI:SS

NlsDateFormat = YYYY-MM-DD HH24:MI:SS



;客户端默认语言，可以解决中文乱码问题 SIMPLIFIED CHINESE_CHINA.ZHS16GBK

NlsLang = SIMPLIFIED CHINESE_CHINA.ZHS16GBK



;是否检查更新消息(广告之类的)，false 不检查

CheckNews = false



;是否检查软件新版本，false 不检查

CheckUpdate = false



;登录框可以选择登录身份，true 显示

UseDBAViews = true



;输出数值转字符串，解决INT64显示为科学计数法问题

NumberFieldsToChar = true

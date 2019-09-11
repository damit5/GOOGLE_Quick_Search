## 介绍

基于py3的 快速使用google进行搜索常用的语句的小jio本

## 搜索语句
```
    "目录遍历漏洞":"site:{example_domain} intitle:index.of",
    "配置文件泄露":"site:{example_domain} ext:xml | ext:conf | ext:cnf | ext:reg | ext:inf | ext:rdp | ext:cfg | ext:txt | ext:ora | ext:ini",
    "数据库文件泄露":"site:{example_domain} ext:sql | ext:dbf | ext:mdb",
    "日志文件泄露":"site:{example_domain} ext:log",
    "备份和历史文件":"site:{example_domain} ext:bkf | ext:bkp | ext:bak | ext:old | ext:backup",
    "SQL错误":'site:{example_domain} intext:"sql syntax near" | intext:"syntax error has occurred" | intext:"incorrect syntax near" | intext:"unexpected end of SQL command" | intext:"Warning: mysql_connect()" | intext:"Warning: mysql_query()" | intext:"Warning: pg_connect()',
    "公开文件信息":"site:{example_domain} ext:doc | ext:docx | ext:odt | ext:pdf | ext:rtf | ext:sxw | ext:psw | ext:ppt | ext:pptx | ext:pps | ext:csv | ext:xlsx | ext:xls",
    "phpinfo()":'site:{example_domain} ext:php intitle:phpinfo "published by the PHP Group',
    "子域名":"site:*.{example_domain}",
    "后台管理":"site:{example_domain} intext: 后台|管理|admin",
    "缓存_1":"cache:http://{example_domain}"
	"缓存_2":"cache:https://{example_domain}"
```
## 使用

`python google_search.py`

logMonitor
==========

log4j日志的监控系统，定时扫描各类log4j日志文件，发生异常将进行邮件短信报警。
基本过程是业务模块定时30秒采用json格式输出到文件，监控系统则定时扫描日志文件。后期考虑采用中间缓存的方式，如memcache或者mysql
或者Redis方式。

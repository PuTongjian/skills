| 模块名称                        | 用途                             | 语法                 | 配置位置         | 例子                                                         | 备注                                            |
| ------------------------------- | -------------------------------- | -------------------- | ---------------- | ------------------------------------------------------------ | ----------------------------------------------- |
| --with-http_stub_status_module  | 监控Nginx服务器的连接状态        | stub_status          | server, location | location /status {<br>	stub_status;<br>}                  | 访问http://host/status即可看到当前Nginx连接状态 |
| --with-http_random_index_module | 从目录中随机选取一个页面作为主页 | random_index on\|off | location         | location / {<br>	root /www;<br>	random_index on;<br> } | 不会随机到隐藏文件                              |
|                                 |                                  |                      |                  |                                                              |                                                 |
|                                 |                                  |                      |                  |                                                              |                                                 |
|                                 |                                  |                      |                  |                                                              |                                                 |


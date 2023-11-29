# SQL盲注自动化脚本

## 文件说明
`blind_int.py` 为整型布尔注入
`blind_str.py` 为字符型布尔注入
`blind_time_int.py` 为整形时间盲注

`blind_time_str.py`为字符型时间盲注

## 脚本使用说明
+ 在脚本中有一个变量为`success_flag`，意味查询成功的页面关键字，脚本将根据此变量来判断查询是否成功。这个变量需要你根据实际情况修改。
+ 脚本中的`base_url`需要根据实际情况进行更改
+ 脚本中的`special_char`需要根据实际情况进行更改
+ `blind_str.py`中的request请求都带上了cookie，如果不需要，请自行删除。

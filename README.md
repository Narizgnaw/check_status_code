# check_status_code
批量检测网站返回状态脚本
需要一张excel表格   第一列为ip（或域名） 第二列为端口号，运行脚本后会输出所有网站的响应状态，支持定义端口段（如：192.168.1.1 81-85）
所有的数据均为文本型
输入输出的文件目录均为脚本所在目录，输出的文件名为“write_status.xls”

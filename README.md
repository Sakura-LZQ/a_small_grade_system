# 简陋的成绩管理系统
大一C语言大作业 成绩管理系统
## 功能简陋
当时想加入好多功能，碍于技术层面，没能实现。  
~~抄了好多篇最后还是让学长重构了~~  
### 功能介绍
1. 录入成绩
2. 删除成绩
3. 修改信息
4. 成绩查询
5. 显示所有成绩信息
6. 保存信息至本地
7. 保存信息并退出

~~值得一提的是 加了一首格格不入的背景音乐~~


## 差点忘了说了 运行需要配置
1. file.txt中的数据，要么全部彻底清空，要么必须在总数，排名数，排序完全正确，且数据项严格用单个空格隔开时，才能正确解析，否则会报错。
2. 学号，姓名，字长不能超过15位，不支持学号和姓名出现重复，不支持汉语，各项分数不要超过int范围。
3. 编译参数必须添加"-lwinmm"。
4. 声音文件放到同源子目录下。

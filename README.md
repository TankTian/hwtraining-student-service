# hwtraining-student-service

## 表格1  培训流程表 training_studentscore  
class_id varchar  前台不显示（前台查询过滤条件）  
status int  0  未完成 1 完成  
hand_people varchar  
role varchar  
task varchar  
deadline varchar  
detail varchar  
comment varchar (前台传入 备注)  

## rest api  
### get hwtraining/v1/studentscore  
输入  
输出  
200 
status int  0  未完成 1 完成  
hand_people varchar  
role varchar  
task varchar  
deadline varchar  
detail varchar  
comment varchar 

# hwtraining-student-service

## 表格1  培训流程表 training_studentscore  
class_id varchar  前台不显示（前台查询过滤条件）  
name varchar  
subject1 varchar  默认0  
subject2 varchar  
subject3 varchar  
subject4 varchar  
subject5 varchar  
subject6 varchar  
subject7 varchar  
subject8 varchar  
subject9 varchar  

## rest api  
### get hwtraining/v1/studentscore  
输入  
class_id varchar 
输出  
200 
class_id varchar  前台不显示（前台查询过滤条件）  
name varchar  
subject1 varchar  
subject2 varchar  
subject3 varchar  
subject4 varchar  
subject5 varchar  
subject6 varchar  
subject7 varchar  
subject8 varchar  
subject9 varchar  

### put hwtraining/v1/studentscore  
输入：
class_id varchar  前台不显示（前台查询过滤条件）  
name varchar  
subject1 varchar  
subject2 varchar  
subject3 varchar  
subject4 varchar  
subject5 varchar  
subject6 varchar  
subject7 varchar  
subject8 varchar  
subject9 varchar  
输出
boolean true/false


# hwtraining-student-service

## 表格1  培训流程表 training_studentscore  
class_id varchar  前台不显示（前台查询过滤条件）    
name varchar   
subject1 int  默认0  
subject2 int    
subject3 int    
subject4 int  
subject5 int  
subject6 int  
subject7 int  
subject8 int  
subject9 int  

## rest api  
### get hwtraining/v1/studentscore  
输入  
class_id varchar 
输出  
200 
class_id varchar  前台不显示（前台查询过滤条件）    
name varchar   
subject1 int  默认0  
subject2 int    
subject3 int    
subject4 int  
subject5 int  
subject6 int  
subject7 int  
subject8 int  
subject9 int  

### put hwtraining/v1/studentscore  
输入：
class_id varchar  前台不显示（前台查询过滤条件）   
name varchar   
subject1 int  默认0   
subject2 int    
subject3 int    
subject4 int  
subject5 int  
subject6 int  
subject7 int  
subject8 int  
subject9 int  
输出
boolean true/false


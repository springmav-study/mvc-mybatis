## 考试系统试题模块
#### 1 试题类型表
*db table name: question_type
*filed: id, name, code
#### 2. 试题表
*table name: question
*table filed: id, question_type_id, title, answer, createdTime, updatedTime
#### 3. 选项表
*table name: option
*table filed: id, question_id, order, isCorrect，createdTime, updatedTime 

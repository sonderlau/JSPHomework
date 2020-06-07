# JSP 期末大作业

---

Created by SonderLau



Made full of love



---



详细信息请参考 **Document** 文件夹下的内容



----

## 后端代码目录

以下内容在github网页内渲染效果比较差 使用文本编辑器查看效果更好



src
 ├── Control
 │   ├── JSONBack.java
 │   ├── Login
 │   │   ├── LoginCheck.java
 │   │   ├── LoginServlet.java
 │   │   └── LogoutServlet.java
 │   ├── Student
 │   │   ├── IndexServlet.java
 │   │   ├── LessonInfo.java
 │   │   ├── OnlineHomework.java
 │   │   └── ResultsSearch.java
 │   └── Teacher
 │       ├── Announcement.java
 │       ├── AssignmentManagement.java
 │       ├── **Assignments.java**
 │       ├── **EnterQuestion.java**
 │       ├── IndexServlet.java
 │       ├── **LessonInfo.java**
 │       ├── StudentManager.java
 │       └── UploadLessonFile.java
 ├── Filter
 │   ├── AutoLogin.java
 │   └── Encoding.java
 ├── Model
 │   ├── Achievements.java
 │   ├── Class.java
 │   ├── Homework.java
 │   ├── Lesson.java
 │   ├── Question.java
 │   ├── User_Student.java
 │   └── User_Teacher.java
 └── utils
     ├── Database
     │   ├── ModelData
     │   │   ├── achievements.java
     │   │   ├── CheckMyHomework.java
     │   │   ├── classQuery.java
     │   │   ├── homework.java
     │   │   ├── lesson.java
     │   │   ├── question.java
     │   │   ├── student.java
     │   │   └── teacher.java
     │   └── SQLConnection.java
     ├── ErrorInfoSet.java
     ├── Perception
     └── string
         ├── KMP.java
         ├── md5String.java
         └── StringModification.java



- Control
  - 都是servlet 用于跳转和控制值传递等
- Model
  - 数据格式规范
- Utils
  - 工具类 包括 数据库 / 字符串加密和处理 等



前端使用 MDUI CSS



**由于目前作业还未截止 为了防止代码被完整拷贝 有部分源码删除了内容**

**会在作业截止之后将代码公开**



---

TODO List

- [x] 方法代码的注释
- [ ] 成绩和答案的自动评判系统
- [x] 作业管理的细节
- [ ] 学生老师端登陆的分离
- [x] 作业管理的逻辑优化
- [x] 学生端后台代码优化
- [x] 前端逻辑设计和数据格式规范
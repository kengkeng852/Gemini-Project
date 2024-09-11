# Gemini-Project
This is a demo project of Spring boot using OCS.
A website for the observatory system to allow scientists and researchers to create a science plan, test a science plan, and Submit a science plan 

# Instruction
- Clone this Github Repository
- Open project as build.gradle
- Run Demo_Application.main() in com/example/demo/DemoApplication.java
- Open web browser: http://localhost:8080/

# Selected use case
- Login
- Create a science plan
- Test a science plan
- Submit a science plan

# Design Pattern
We used Singleton design pattern for our project because it enable us to ensure that a class has only one instance while providing a global access point to this instance. This design pattern prevent other objects use new operator.
- UserController.java where the ocs is a single instance that is accessible to all clients.
- SciencePlanController where the ocs is a single instance that is accessible to all science plans.

![image](https://github.com/user-attachments/assets/0824a7d2-547b-4641-8e23-0197235d1aad)

![image](https://github.com/user-attachments/assets/e858b3d5-7392-4b9a-80ae-971fc22cb89b)

![image](https://github.com/user-attachments/assets/242d28b5-2ff7-4bef-b241-dd4c0ed8f654)

![image](https://github.com/user-attachments/assets/e76f630d-9a96-407d-b0c3-294e7d1075b2)




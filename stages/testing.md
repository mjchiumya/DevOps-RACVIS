# __RACIVS matrix for DevOps Pipelines__   

<img src="https://user-images.githubusercontent.com/10748736/112030685-6c81be80-8b32-11eb-94b8-c2c01b8f4581.png">

## __Pipeline stage:__  Test  
### __Stage description:__  
This phase involves testing implemented code

R = Responsible - The role responsible for doing a particular task for the project
A = Accountable - The role who makes sure that tasks assigned are being done
C = Consulted -  The role consulted prior to decisions being made
I = Informed -  The role receiving information on the progress and result of a task
V = Verifier - The role who verifies that acceptance criteria is met for the finished tasks.
S = Signatory - The role who approves product deliverable/task completion.

| Pipeline Stage:<br>Plan  |Software Developer  | Software Designer  |Project Manager  |Srum Master  | User    | Product Owner    |
|------------------------  |------------------- |------------------- |---------------- |------------ |-------- |-----------------
| Unit Testing             |         R          |        A           |       S         |     CI      |         |        V         |
| Integration Testing      |         CI         |        R           |       S         |     V       |         |        A         |
| User Acceptance Tesing   |         A          |        I           |       C         |     V       |   S     |        R         |

              
  
  
[Home](../index.md)  

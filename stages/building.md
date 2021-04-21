# __RACIVS matrix for DevOps Pipelines__   

<img src="https://user-images.githubusercontent.com/10748736/112030685-6c81be80-8b32-11eb-94b8-c2c01b8f4581.png">

## __Pipeline stage:__  Build  
### __Stage description:__  

Build is the phase where developer build the code implemented 
R = Responsible - The role responsible for doing a particular task for the project
A = Accountable - The role who makes sure that tasks assigned are being done
C = Consulted -  The role consulted prior to decisions being made
I = Informed -  The role receiving information on the progress and result of a task
V = Verifier - The role who verifies that acceptance criteria is met for the finished tasks.
S = Signatory - The role who approves product deliverable/task completion.


| Pipeline Stage:<br>Plan  |Software Developer  | Software Designer  |Project Manager  |Srum Master  | User    | Product Owner    |
|------------------------  |------------------- |------------------- |---------------- |------------ |-------- |-----------------
| Perform Commit           |         R          |        S           |       V         |     A       |         |        CI         |
| Create pull Request      |         R          |        CI          |       S         |     V       |         |        A          |
| Code Review/Merge        |         CI         |        R           |       V         |     A       |         |        S          |

                    
  
  
[Home](../index.md)  

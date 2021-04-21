# __RACIVS matrix for DevOps Pipelines__   

<img src="https://user-images.githubusercontent.com/10748736/112030685-6c81be80-8b32-11eb-94b8-c2c01b8f4581.png">

## __Pipeline stage:__  Release  
### __Stage description:__  
this phase involves deploying build into the production environment

R = Responsible - The role responsible for doing a particular task for the project
A = Accountable - The role who makes sure that tasks assigned are being done
C = Consulted -  The role consulted prior to decisions being made
I = Informed -  The role receiving information on the progress and result of a task
V = Verifier - The role who verifies that acceptance criteria is met for the finished tasks.
S = Signatory - The role who approves product deliverable/task completion.

| Pipeline Stage:<br>Plan  |Software Developer  | Software Designer  |Project Manager  |Srum Master  | User    | Product Owner    |
|------------------------  |------------------- |------------------- |---------------- |------------ |-------- |-----------------
| Feature Flagging         |              S     |          V         |       R         |       CI    |         |        A         |
| Activation/deactivation  |              R     |          S         |       V         |       A     |         |        CI        |
| Installation             |              A     |          R         |       CI        |       S     |         |        V         |
| Update                   |              V     |          CI        |       A         |       R     |         |        S         |

  
[Home](../index.md)  

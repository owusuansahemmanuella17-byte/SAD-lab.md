graph TD
```mermaid
flowchart TD
    Manager[Manager] -->|Assigns Project| Team[Team]
    Team -->|Distributes| Employee1[Employee 1]
    Team -->|Distributes| Employee2[Employee 2]
    Team -->|Distributes| Employee3[Employee 3]
    Employee1 -->|Responsibility| Task1[Task 1]
    Employee2 -->|Responsibility| Task2[Task 2]
    Employee3 -->|Responsibility| Task3[Task 3]
    Task1 -->|Missing Info Discovered| Communication[Team Communication]
    Task2 -->|Missing Info Discovered| Communication
    Task3 -->|Missing Info Discovered| Communication
    Communication -->|Collaborate| Resolution[Problem Solving]
    Resolution -->|Resolved| FinalProject[Final Project]
    FinalProject -->|Present| Manager
    

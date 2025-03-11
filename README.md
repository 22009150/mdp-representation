# MDP REPRESENTATION

## AIM:
To create a MDP (Markov Decision Process) for the undertaken problem statement

## PROBLEM STATEMENT:
Getting Runs in Cricket

### Problem Description
The batsman aims to score runs by hitting the ball and running between the wickets while avoiding dismissal by the fielding team.

### State Space
6,Run,Wicket

### Sample State
Run

### Action Space
Batting,Catching ball

### Sample Action
Batting

### Reward Function
Score

### Graphical Representation
![WhatsApp Image 2025-03-11 at 19 18 06_efe187aa](https://github.com/user-attachments/assets/fee62233-878d-4328-94c5-cfc534c135f8)


## PYTHON REPRESENTATION:
```
m= {
    0: {
        0: [(1.0, 0, 0.0, True)],  
        1: [(1.0, 0, 0.0, True)]
    },
    1: {
        0: [(0.2, 1, 0.0, False), (0.8, 1, 0.0, False)],  
        1: [(0.2, 1, 0.0, False), (0.8, 1, 0.0, False)]
    },
    2: {
        0: [(1.0, 2, 1.0, True)],
        1: [(0.8, 2, 0.0, True)]
    }
}


```

## OUTPUT:
![image](https://github.com/user-attachments/assets/6cf38e23-ac13-4c1f-84a2-dc89a64f2f17)


## RESULT:
Thus, the MDP for a stochastic model (game) using python is implemented successfully


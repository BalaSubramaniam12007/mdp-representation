# MDP REPRESENTATION

## AIM:
The representation of real world scenario using Markov Decision Process by stating all the states,actions and environment with respective rewards.

## PROBLEM STATEMENT:
```
Developed By BALASUBRAMANIAM ;
Registration No: 212224240020
```
### Problem Description
A Man who is standing on the road which is a junction point and thinking about whether to walk left or right

### State Space
{0,1,2} = {Left way,Current position, Right way}

### Sample State
{1} = {Current position}

### Action Space
{0,1,2} = {Walking to left , Being in current position , Walking to right} 

### Sample Action
{2} = {Walking to right}

### Reward Function
+1 If he reaches the goal state that is walking to right way
0 Otherwise

### Graphical Representation
<img width="1536" height="1024" alt="ChatGPT Image Aug 30, 2025, 11_32_27 AM" src="https://github.com/user-attachments/assets/1157eebf-41d7-465d-9c6b-9dccdd2b9b78" />

## PYTHON REPRESENTATION:
```
# Creating Dictionary
P={
    0:{
        0:[(1.0,0,0,False)],
        1:[(1.0,0,1,False)]
        
    },
    1:{
        0:[(0.8,0,0,False),(0.2,2,0,True)],
        1:[(0.8,2,1,True),(0.2,0,1,False)]
       
    },
    2:{
        0:[(1.0,2,0,False)],
        1:[(1.0,2,1,False)]
       
    }
}
```

### OUTPUT:
<img width="359" alt="image" src="https://github.com/user-attachments/assets/46d98b31-7aaa-41ef-8b01-3823dc52d302">


### RESULT:
Therefore an MDP representation has been created for a real world scenario with all the states, actions and rewards.






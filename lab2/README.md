# Lab 2 - Set Covering (by means of EA)

## Task

Given a number $N$ and some lists of integers $P = (L_0, L_1, L_2, ..., L_n)$, 
determine, if possible, $S = (L_{s_0}, L_{s_1}, L_{s_2}, ..., L_{s_n})$
such that each number between $0$ and $N-1$ appears in at least one list

$$\forall n \in [0, N-1] \ \exists i : n \in L_{s_i}$$

and that the total numbers of elements in all $L_{s_i}$ is minimum. 

--------------------------------------------------------------

Group Members: Milad Zakhireh (300708), Masoud Karimi (300283)

--------------------------------------------------------------

### Results
| N    | weight | nodes                                                                                                      |
|------|--------|------------------------------------------------------------------------------------------------------------|
| 5    | 5      | [(3,) (1,) (4,) (0, 2)]                                                                                    |
| 10   | 10     | [(2, 5) (1, 7) (0, 4) (3, 6, 8, 9)]                                                                        |
| 20   | 29     | [(2, 6, 8, 10, 12, 15, 18) (0, 1, 3, 7, 9, 10, 11, 15)(1, 3, 8, 11, 14, 19) (4, 5, 8, 13, 15, 16, 17, 19)] |
| 100  | 244    | many nodes                                                                                                 |
| 500  | 1739   | many nodes                                                                                                 |
| 1000 | 3980   | many nodes                                                                                                 |


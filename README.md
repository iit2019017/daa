# DAA Assignments

**Team Members**
|   Enrollment No.  |   Name   | GithubId |
|   --------------  |   ----   | -------- |
|    IIT2019015  |   Aakash Anand | aakashanand7 |
|    IIT2019016  |   Parth kataria | ParthKataria | 
|    IIT2019017  |   Shruti Nanda | Saggittarius-A  |

**Group No-**"05"

**Faculty Name-**"Md Javed"

**Mentor Name-** "Md. Meraz"

---
## This Repo is for aubmitting all of our DAA assignment and all of our Assignment is evaluated by our TA meraz. 
---

```
#Download project
git clone https://github.com/iit2019017/daa 
```
Project Initialize 
```
cd daa
#create assignment-1 folder
mkdir assignment_01

#go to assignment-1
cd assignment_01

#Create file
touch readme.md

.
.
```
---

Run the code
```
Brute_Force.cpp
Sorting_and_Searching.cpp
```
Output
```
Union of two array
```
---

**Test case**

Find Union
```
Test Case-1
Input:
2
3
3 4 
2 7 5
Out:
3 4 2 7 5
#--------------------------#
Test Case-2
Input:
3 
4
2 3 5
3 5 6 7
Out:
2 3 5 6 7
```

---

### Theory
 Given two graphs G1 = (V1, E1) and G2 = (V2, E2) we define the ring sum G1 ⊕ G2 = (V1 ∪ V2,(E1 ∪ E2) − (E1 ∩ E2)) with isolated points dropped. So an edge is in G1 ⊕ G2 if and only if it is an edge of G1 , or an edge of G2, but not both.

---

### Analysis

**Time Complexity**

The algorithms were tested against positive random sets of variable sizes.The result thus obtained from this experiment is given below:

For brute():

- Best case : Ω(n+m)
- Average case : θ(n+n*m)
- worst case : O(n+n*m)

For union():

- Best case : Ω(n+m)
- Average case : θ(n(logn + 1) +m(logm + 1))
- Worst case : O(n(logn + 1) +m(logm + 1)


For Searching and sorting

- Best case : Ω(mlogm+n)
- Average case : θ((m+n)log(min(m,n)))
- Worst case : O((m+n)log(min(m,n)))



**Space Complexity**

For Brute : O(n)

For Union : O(n)

For searching and sorting : O(n)

---

### References

1. https://www.geeksforgeeks.org/union-and-intersection-of-two-sorted-arrays-2/
2. https://www.google.com/search?q=Ringsum+operation+on+two+sets+of+positive+integers&oq=Ringsum+oper&aqs=chrome.1.69i57j69i59l2.7684j0j7&sourceid=chrome&ie=UTF-8



Sahil is in the mood to attend Geeks Classes. He reaches venue of Geeks Classess. Now, he is confused about his sitting place. There are two columns of students sitting in the classes. Each student has been assigned a score on the basis of their score in Geeks Class Entrance Contest. Now, he wants to sit in the row which contains students with maximum score. Help him in finding the desired column.

Input : First line of Input contains testcase "T". For each testcase "T", there will be 3 lines of input, first line contains lengths of the columns, and next two lines contains the scores of students sitting in that column.

Output : For each testcase, Output the column in which Sahil should sit.

Constraints :
1 <= T <= 100
1 <= N1, N2 <= 10000
1 <= score <= 1000000

Example :
Input :
2
5 6
8 4 5 6 7
2 3 4 5 6 7
3 5
100 29 37
100 200 300 400 500
Output :
C1
C2

Explanation :
TestCase 1 : In 1st column sum of score of students is 30 which is more than 2nd column (score = 27).

TestCase 2 : In 2nd column sum of score of students is 1500 which is more than 1st column (score = 166).

 


```python
T=int(input())
n=0
while(n<=1):
    
    C=list(map(int,input().split()))
    C1=sum(list(map(int,input().split())))
    C2=sum(list(map(int,input().split())))
    if C1>C2:
        print ("C1")
    else:
        print("C2")
    n=n+1

```

    2
    5 6
    8 4 5 6 7
    2 3 4 5 6 7
    C1
    3 5
    100 29 37
    100 200 300 400 500
    C2
    


```python

```

## [Assignment 1: Fuzzy Scheduling](ass1/20T2_assignment1.pdf)
### basic idea
 - 用python实现一个能帮你解决[CSP](https://zh.wikipedia.org/wiki/%E7%BA%A6%E6%9D%9F%E8%A1%A5%E5%81%BF%E9%97%AE%E9%A2%98)的脚本!


### Prequisite Knowledge
 - What is : (*If you dont know, check the lecture slides/notes or google it.*)
    - CSP
    - Backtracking Search
    - Arc Consistency
    - A* search algorithm
    



### What you need to do
你需要写:
 - fuzzyScheduler.py: 
    - Usage: `python3 fuzzyScheduler.py input1.txt > output1.txt`

    
   
还需要写一些  
 - 测试集(input1.txt, output1.txt, input2.txt, output2.txt, etc.)
    - input.txt
    - output.txt
          


### Idea of fuzzyScheduler.py
    # 1. Transfer the txt to python object: get input text and create the csp
    # 2. AC and domain splitting
    # 3. Use A star algorithm to solve the problem
    # 4. Print the solution
        


### How to start

1. Play around with aipython([code](ass1/aipython.zip) | [pdf](ass1/aipython.pdf)):  
Know how to use these functions:
  
        from cspConsistency import Search_with_AC_from_CSP
        from cspProblem import CSP, Constraint
        from searchGeneric import AStarSearcher

1. .....(to be finished)


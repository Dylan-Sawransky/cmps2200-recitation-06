# CMPS 2200 Recitation 06
## Answers

**Name:**_______Dylan Sawransky__________
**Name:**_________________________


Place all written answers from `recitation-07.md` here for easier grading.



- **2)**
W(n) = work to compute fibonacci sequence n = 0 or n = 1 will just return 1 but for other numbers it is 
W(n) = W(n−1)+W(n−2)+theta(1)
- **3)**
S(n)=max(S(n−1),S(n−2))+Θ(1),S(0)=theta(1),S(1)=theta(1)
S(n)=Θ(n)
- **4)**
The entries follow the fibonacci sequence the number of times f_i is computed is afibonacci number.
- **6)**
Each fib_top_down(i) that actually does work is called at most once. work= theta(n) span= theta(n)
- **8)**
Every Fi is only read (O(1)) times work = theta(n) span = theta(n)

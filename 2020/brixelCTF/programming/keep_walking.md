# Keep Walking.....

Category: Programming

Points: 10

Description:

> This is a challenge to test your basic programming skills.

> Pseudo code:

> Set X = 1

> Set Y = 1

> Set previous answer = 1


> answer = X * Y + previous answer + 3


> After that => X + 1 and Y + 1 ('answer' becomes 'previous answer') and repeat this till you have X = 525.


> The final answer is the value of 'answer' when X = 525. Fill it in below.


> Example:

> 5 = 1 * 1 + 1 + 3

> 12 = 2 * 2 + 5 + 3

> 24 = 3 * 3 + 12 + 3

## Solution

This problem looks same to the process of Fibonacci Sequence. X and Y is equal to the iteration of the loop, the previous answer is the sum from the previous iteration and constant plus 3. So I made a python script to make the process faster.

The Formula is:
`answer = X * Y + previous answer + 3`

```
sum = 1
for i in range(1, 526):
    sum += ((i*i)+3)
    print(str(sum) +" = "+str(i)+" x "+str(i)+" + "+str(sum-((i*i)+3))+" + 3") #Debug Mode
```

The flag is `brixelCTF{48373851}`
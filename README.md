
'''
A die marked A to E is rolled 50 times. Find the probability of getting a “D” exactly 5
times.
'''

# 4.5
import math
x=5
n=50
y=(1/x)**x * ((x-1)/x)**(n-x) * (math.factorial(n)/(math.factorial(x)*math.factorial(n-x)))
print(y)

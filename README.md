# LD-problems
```
def testMe(nums):
    # return a list with the following values [3,4,5,6]
    
    lst = []
    for i in nums:
        lst.append(i + 2)
        
    return lst
    
nums = [1,2,3,4]
print(testMe(nums))
```
-------
```
def testMe(nums):
    # return a list with the following values ["3","4","5","6"]
    
    lst = []
    for i in nums:
        test = (int(i) + 2)
        lst.append(str(test))
    return lst
    
nums = ["1","2","3","4"]
print(testMe(nums))
```
--------


# LD-problems
```
# 1
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
# 2
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
```
# 3
def testMe(nums):
    # return a list of numbers greater than 6
    
    lst = []
    for i in nums:
        if i > 6:
            lst.append(i)
    return lst
    
nums = [4,5,6,8,9]
print(testMe(nums))
```
-------
```
# 4
def testMe(nums):
    # return a list of numbers greater than 6
    
    lst = []
    for i in nums:
        if int(i) > 6:
            lst.append(i)
    return lst
    
nums = ["4","5","6","8","9"]
print(testMe(nums))
```
------
```
# 5
def testMe(nums):
    # return a range of numbers from 7 to 23
    
    return (nums[4:9])
    
nums = [3,4,5,6,7,8,11,14,23,45,76]
print(testMe(nums))
```
-----
```
# 6
def testMe(nums):
    # if the last number is 76, return "Yes!", else return -1
    
    for i in nums:
        if nums[-1] == 76:
            return "Yes"
    return -1
    
nums = [3,4,5,6,7,8,11,14,23,45,76]
print(testMe(nums))
```
-------
```
# 7
def testMe(nums):
    # return a list of only odd numbers
    
    lst = []
    
    for i in nums:
        if i % 2 == 0:
            continue
        else:
            lst.append(i)
    return lst
    
nums = [3,4,5,6,7,8,11,14,23,45,76]
print(testMe(nums))
```
------
```
def testMe(nums):
    # get the key and value of the elements in the list
    # return ['key:value', 'key:value'] or [(key:value), (key:value)]
    
    lst = []
    
    for key, value in enumerate(nums):
        # lst.append(f"{key}:{value}")
        test = (key,value)
        lst.append(test)

    return lst
    
nums = [3,4,5,6]
print(testMe(nums))
```

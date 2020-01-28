# Introduction to Data Engineering

---
### Python Bubblesort

``` python
# Python program for implementation of Bubble Sort
 
def bubbleSort(arr):
    n = len(arr)
 
    # Traverse through all array elements
    for i in range(n):
 
        # Last i elements are already in place
        for j in range(0, n-i-1):
 
            # traverse the array from 0 to n-i-1
            # Swap if the element found is greater
            # than the next element
            if arr[j] > arr[j+1] :
                arr[j], arr[j+1] = arr[j+1], arr[j]
 
# Driver code to test above
arr = [64, 34, 25, 12, 22, 11, 90]
 
bubbleSort(arr)
 
print ("Sorted array is:")
for i in range(len(arr)):
    print ("%d" %arr[i]), 
```

---

# Data, Baby!

- Ideas for course
- things to look forward to
- 12 weeks of Hell

---

## Foo Bar (Two Section)

--

#  Clean Vertical

- foo
- bar
- baz

--

## A Helicopter

- a aircraft that uses an over-head propeller to maintain airworthiness
- too loud for civilization

---

## Three Section

---

## Hateful Eight

- this is a bullet
- this is another bullet

---

#### Hateful Four

- this is a bullet
- this is another bullet

``` python
if foo > bar :
    print "helloe worlde"
```

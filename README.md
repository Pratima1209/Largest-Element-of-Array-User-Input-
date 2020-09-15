# Largest-Element-of-Array-User-Input-

# Python Program to find largest element in an array (with User input)

arr=[] 
a=int(input("Enter Number of Element :"))
for i in range(a):
    arr.append(int(input("Enter Element in array :")))

n=len(arr)
    
def _max(arr,n):
    max=arr[0]
    for i in range(1,n):
        if arr[i]>max:
            max=arr[i]
    return max
ans=_max(arr,n)
print("Largest Element of Array = {0} is {1}".format(arr,ans))

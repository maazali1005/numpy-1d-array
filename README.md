
# Numpy-operations-on-1d-array
#1D array operations

print("1D array operations")

arr1D=np.array([1,2,3,4,5])

print("original 1D array:",arr1D)

print("shape:",arr1D.shape)

print("size:",arr1D.size)

print("data type:",arr1D.dtype)

print("sum:",np.sum(arr1D))

print("min:",np.min(arr1D))

print("max:",np.max(arr1D))

print("mean:",np.mean(arr1D))

print("Standard Deviation:",np.std(arr1D))

print("Reshaped (5,1):\n",arr1D.reshape(5,1))

print("Reversed:",arr1D[::-1])

print("Transpose",arr1D.T)

print()

O/P:

1D array operations

original 1D array: [1 2 3 4 5]

shape: (5,)

size: 5

data type: int32

sum: 15

min: 1

max: 5

mean: 3.0

Standard Deviation: 1.4142135623730951

Reshaped (5,1):

[[1]

[2]

[3]

[4]

[5]]

Reversed: [5 4 3 2 1]

Transpose [1 2 3 4 5]
# numpy-1d-array

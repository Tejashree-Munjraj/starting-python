# starting-python
creating a numpy array
import numpy as np
 
# Create a NumPy array
arr = np.array([1, 2, 3, 4, 5])
 
# Print the array
print("Original array:", arr)
 
# Perform some operations
mean_value = np.mean(arr)
sum_value = np.sum(arr)
square_root = np.sqrt(arr)
 
# Print the results
print("Mean:", mean_value)
print("Sum:", sum_value)
print("Square root:", square_root)

OUTPUT:
Original array: [1,2,3,4,5]
Mean: 3.0
Sum: 15
Square root: [1.         1.41421356 1.73205081 2.         2.23606798]

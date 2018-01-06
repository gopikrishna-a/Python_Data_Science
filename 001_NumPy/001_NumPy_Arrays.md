# NumPy Arrays

* NumPy Arrays comes in two types i.e 1D and 2D

Creating NumPy array using python object such as list

import numpy as np

my_list = [1, 2, 3] #normal python list

#Casting python list into array 

import numpy as np

arr = np.array(my_list)
print(arr)

#Casting 2D list into array 
my_mat = [[1, 2, 3], [4, 5, 6], [7, 8, 9]]

np.array(my_mat)
print(my_mat)



==========================================================

np.arange(0, 10)

np.zeros(4)

np.zeros((3, 4))

np.ones(4)

np.ones((3, 4))


==========================================================
#3 rd  areg is no. of points
np.linspace(0, 5, 10)


==========================================================

# Creating identity matrix
#takes one arg
np.eye(4)


===========================================================
#Creating arrays of random numbers (Uniform distribuation)
#1D
np.random.rand(5)

#2D
np.random.rand(5, 5)

#Creating arrays of random numbers (Noramal distribuation)
#1D
np.random.randn(5)

#2D
np.random.randn(5, 5)

=============================================================


np.random.randint(1, 100)

np.random.randint(1, 100, 10)

============================================================
arr = 
arr.max()
arr.min()

arr.argmax()
arr.argminax()
arr.shape()
arr = arr.reshape()

arr.dtype












# DSA
90 Day Challenge

<h2> 1. What is Data Structure ? </h2>
  <p> A data structure is a storage that is used to store and organize data. It is a way of arranging data on a computer so that it can be accessed and updated efficiently. </p>


<h2> 2. What is an algorithm? </h2>
<p> An algorithm is a step by step method of solving a problem or manipulating data. It defines a set of rules for a computer program to accomplisha task. </p>

                Example:     Input --->   calculation -----> Stop When answer fond.

<h2> 3. Why are DSA inportant ? </h2>

<p> Repeat Defination q1 and q2 </p>


<h2> 4.Type of Data Structures </h2>

![image](https://user-images.githubusercontent.com/95286756/212731151-cd18a90b-bb27-48a9-84d8-d961e8465ecb.png)

<h2> 5.Primitive Data Structures? </h2>
<p> Primitive data structures allow storing only one value at a particular location. Primitive data structures of any programming language are the data types that are predefined in that programming language. </p>

![Screenshot 2023-01-16 225850](https://user-images.githubusercontent.com/95286756/212737110-c4967809-821c-4e0f-b8be-4891548eda52.jpg)

<h2> 6. Types of Algorithms </h2>
<p> 
1. Brute Force Algorithm <br>
2. Recursive Algorithm  <br>
3. Randomized Algorithm  <br>
4. Sorting Algorithm  <br>
5. Searching Algorithm <br>
6. Hashing Algorithm <br>

</p>

<h1> Day 2 </h1>
<h2> 7. Arrays </h2>
<p> Arrays are defined as the collection of similar type of data items stored at contiguous memory location. 
  Array is the simplest data structure where each data element can be accessed by using its index number. </p>
  
  ![image](https://user-images.githubusercontent.com/95286756/212951019-92f0d688-c952-43e7-9c87-5f87ed98414e.png)
  
  <h2> 8. Types of Arrays ? </h2>
  <p>  There are majorly two types of arrays  <br>
  1. One-Dimensional Arrays:  A One-Dimensional Array is the simplest form of an Array in which the elements are stored linearly and can be accessed individually by specifying the index value of each element stored in the array.<br>
  2. Multi-Dimensional Arrays: A multi-dimensional array can be termed as an array of arrays that stores homogeneous data in tabular form. Data in multidimensional arrays are stored in row-major order. 
  <p>

<h2>  Create an Arrays ? </h2>
<p> 
  When we create an array , we <br>
> Assign it to a variable  <br>
> Define the type of elements that it will store <br>
> Define the size (the max number of elements)
</p>

from array import* <br>
arrayName = array (typecode, [Initializers])
<p> </p>
``from array import *
myArray = array('i',[1,2,34,55,6,87,])
myArray1 = array('d',[1,2,34,55,6,87,])
print(type(myArray))
print(myArray)
print(myArray1)

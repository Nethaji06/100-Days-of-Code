### Statement
~~~
Distance between two points
Write a program to calculate the distance between two points.
To find the distance between two points (x1,y1) and (x2,y2), all that you need to do is use the coordinates of these ordered pairs and apply some common sense. 
Begin with the most simplest formula and then incrementally arrive at the correct formula as you solve the test cases.
~~~
### Input &output
~~~
INPUT 
4
0
0
0
OUTPUT
4

INPUT 
0
0
4
3
OUTPUT
5
~~~

### Code
~~~
import math
# get the x coordinate of Point 1
x1 = int(input())  
# get the y coordinate of Point 2
y1 = int(input())  
# get the x coordinate of Point 2
x2 = int(input())  
# get the y coordinate of Point 2
y2 = int(input())  
# Write the code to calculate distance between 
# the two points 
distance = math.sqrt( ((x1-x2)**2)+((y1-y2)**2) )
print(distance)
~~~

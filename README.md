# Assignment
# 1. Micro and Array Update
Micro purchased an array A having N integer values. After playing it for a while, he got bored of it and decided to update value of its element. In one second he can increase value of each array element by 1. He wants each array element's value to become greater than or equal to K. Please help Micro to find out the minimum amount of time it will take, for him to do so.

# Input:
First line consists of a single integer, T, denoting the number of test cases. First line of each test case consists of two space separated integers denoting N and K. Second line of each test case consists of N space separated integers denoting the array A.

# Output:
For each test case, print the minimum time in which all array elements will become greater than or equal to K. Print a new line after each test case.

1<=T<=5 1<=T<=10^5 1<=A[i] k<=10^6

# Sample Input:
2

3 4

1 2 5 3 2 2 5 5

# Sample output:
3 0

# 2. Hamiltonian and Lagrangian
Students have become secret admirers of SEGP. They find the course exciting and the professors amusing. After a superb Mid Semester examination, it’s now time for the results. The TAs have released the marks of students in the form of an array, where arr[i] represents the marks of the ith student.

Since you are a curious kid, you want to find all the marks that are not smaller than those on its right side in the array.

# Input Format:
The first line of input will contain a single integer n denoting the number of students. The next line will contain n space separated integers representing the marks of students.

# Output Format:
Output all the integers separated in the array from left to right that are not smaller than those on its right side.

# Constraints:
1 <= n <= 1000000

0 <= arr[i] <= 10000

# Sample Input:
6

16 17 4 3 5 2

# Sample output:
17 5 2

# 3. Frustrated coders
There are N frustrated coders standing in a circle with a gun in their hands. Each coder has a skill value S[ i ] and he can only kill those coders that have strictly less skill than him. One more thing, all the guns have only 1 bullet. This roulette can take place in any random order. Fortunately, you have the time stone (haaan wo harre wala) and you can see all possible outcomes of this scenario. Find the outcome where the total sum of the remaining coder's skill is minimum. Print this sum.

# Input Format:
The first line contains N the no. of coders The next line contains N elements where the ith element is theS[ i ] of ith coder.

# Output Format:
Print a single line containing the minimum sum.

# Constraints;
1<= N <= 1000000

1<=S[ i ]<=1000

# Sample Input:
6

1 7 2 2 4 4

# Sample Output:
11

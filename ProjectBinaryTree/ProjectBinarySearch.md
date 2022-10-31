# Write down binary search tree construction phases of the given array. [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]
Construction of binary tree is based on a simple principle. Firstly, a root node is selected, then every element of the given array is placed either right side or the left side of the root node according to their values. As the name of the algorithm implies every node can only have two branches; and each element greater than the node that is being compared is placed under the right branch of the node, and reverse is applied for the lesser elements.

The array is not sorted, therefore root is selected randomly as 6. Binary search tree is constructed by using the given arrays order. 

7 is greater than the root therefore it goes to right side of the root, 5 is less than the root therefore it goes to left side of the root. 1 is less than the root and it is less than 5 therefore it goes to left side of 5 and 8 is greater than the root and 7 therefore it goes to riht side of seven. According to above instance; visual represantation of the whole set is illustrated below.

					      6
					     / \
					    5   7
					   / 	  \
					  1	   8
					 / \	    \
					0    3	     9
					    / \
					   2   4

# Project Merge Sort
## 1. Write down sorting steps of the given array.
### Given array to be sorted is [16,21,11,8,12,22]
### step 1: Firstly, the algorithm would divide the array by two to get two arrays which consists of three items. Then the algorithm continues the division expression on those newly created lists until it gets atomic elements of the lists. Visual representation of the above explanation is shown below.
1. divide [16,21,11] [8, 12, 22]
2. divide [16, 21], [11], [8, 12], [22]
3. divide [16], [21], [11], [8], [12], [22]

### step 2: At this step, the algorithm would compares items in each list and sorts them accordingly. Another words, the merging process starts at his point. 
     merge [16],[21],[11],[8],[12],[22]
	          \  /     |     \  /    |
	           \/      |      \/     |
	    
     merge [16, 21],[11],[8,12], [22]
	            \    /      \     /	
	             \  /        \   /
                  \/	  \ /
     merge    [11,16,21]   [8,12,22]
		        \           / 
		         \         /
		          \       /
		           \     /
      merge      [8,11,12,16,21,22]
## 2. Write down big o notation of the sorting method.
The algorithm had worked logn times to divide given array.
Besides it had worked n times to merge 

### Therefore, Big O Notation for the given algorithm is O(nlogn)




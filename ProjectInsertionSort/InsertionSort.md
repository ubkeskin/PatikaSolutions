# Project Insertion Sort
## 1. Write down sorting steps of the given array.
### Given array to be sorted is [22,27,16,2,18,6]
### step 1: [[2],[27,16,22,18,6]] -> In order to find smallest number the algorithm would work on n-1 items of the array.
### step 2: [[2, 6],[16,22,18,27]] -> n-2
### step 3: [[2, 6, 16],[22,18,27]] -> n-3
### step 4: [[2, 6, 16, 18],[22,27]]
### step 5: [[2, 6, 16, 18, 22],[27]]
## 2. Write down big o notation of the sorting method.
### The algorythm had worked n + (n -1) + (n-2) ... (n- (n-1)) times.
### This expression can be evaluate by the function written below.
### n*(n+1)/2 = (n^2+n)/2
### Big O Notation for the given algorythm is O(n^2)
## 3. We have defined 3 cases during the tutorials. Firstly, best case, which means that the term that is being searched is to be placed at the beginning of the given array. Secondly, avarage case, which means that the term that is being searched is to be placed at the middle of the given array. Lastly, worst case, which means that the term that is being searched is to be placed at the end of the given array.
## 4. After the array above is sorted, how do you describe sorting of "18" according to cases mentioned above.
### Avarage case.
## 5. An array [7,3,5,8,2,9,4,15,6]  is given. Write down first 4 steps of the sorting function according to insertion sort algorythm.
### step 1: [2,3,5,8,7,9,4,15,6]
### step 2: [2,3,5,8,7,9,4,15,6]
### step 3: [2,3,4,8,7,9,5,15,6]
### step 4: [2,3,4,5,7,9,8,15,6]




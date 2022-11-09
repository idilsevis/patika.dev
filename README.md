# patika.dev
# [22,27,16,2,18,6] Insertion Sort 
minimum=2	2 & 22 change their place [2, | 27, 16, 22, 18, 6] 
minimum=6 6 & 27 change their place [2, 6, | 16, 22, 18, 27] 
minimum=16 there is no need to change in placement [2, 6, 16, | 22, 18, 27]
minimum=18 18 & 22 change their place [2, 6, 16, 18, 22, 27]
 # Big-O
n	           1.step
n-1	         2.step
n-2	         3.step
.              .
.              .
.              .
1             n-1.step
Total operation is equal to (n*(n-1))/2		O(n^2) 
#Time Complexity
Worst Case 
# [7,3,5,8,2,9,4,15,6] Insertion Sort first 4 steps
minimum=2	2 & 7 change their place [2, | 3, 5, 8, 7, 9, 4, 15, 6]
minimum=3	there is no need to change in placement [2, 3, | 5, 8, 7, 9, 4, 15, 6] 
minimum=4	4 & 5 change their place [2, 3, 4, | 8, 7, 9, 5, 15, 6]
minimum=5	5 & 8 change their place [2, 3, 4, 5, | 7, 9, 8, 15, 6]
#[16,21,11,8,12,22]	Merge Sort 
[16,21,11]		  [8,12,22] 
[11] [16,21]		[8] [12,22]
[11] [16] [21]		[8] [12] [22]
--  --  --  --  --  --  --  --  --  --  --  --  --  --  --  
[11,16,21]		[8,12,22]
Consequently, sorting is [8,11,12,16,21,22]
#Big-O
O(nlogn)

#3
   7
  /
 5 
  

    7
   /
  5
 /
1 


    7
   / \
  5   8
 /
1 


    7
   / \
  5   8
 / 
1  
 \
  3


      7
     / \
    5   8
   / \
  1   6
 / \
0   3


      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3


      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
     \
      4


      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
   / \
  2   4








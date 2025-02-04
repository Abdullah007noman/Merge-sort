# Merge-sort

Let's walk through how the algorithm works on our array [5,2,4,7,1,3,2,6]:

* First split: [5,2,4,7] and [1,3,2,6]
* Split left half: [5,2] and [4,7]

    * Split again: [5] and [2] → merge to [2,5]
    * Split again: [4] and [7] → merge to [4,7]
    * Merge [2,5] and [4,7] → [2,4,5,7]


* Split right half: [1,3] and [2,6]

    * Split again: [1] and [3] → merge to [1,3]
    * Split again: [2] and [6] → merge to [2,6]
    * Merge [1,3] and [2,6] → [1,2,3,6]


* Final merge: [2,4,5,7] and [1,2,3,6] → [1,2,2,3,4,5,6,7]

  

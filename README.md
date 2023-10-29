# QUESTION-02
Sorting a list of numbers


-Start


-initializing an array of numbers naming list


-the numbers in the list are= [23,12,45,30,10,19,55,96]


-by using merge sort


-the first thing merge sort does is check if the size of an array is greater than 1 if it is, it splits the array into two halves


-our array size is 8 it gets split into two arrays of size 4


-these are still bigger than size 1 so they get split again into arrays of size 2


-finally they split into 8 arrays with one item in each


-starting with the first two arrays 23 and 12 as 12 is smaller we take it as first value and put 23 as second value


-the next two arrays are 45 and 30 as 30 is smaller we take it as first value and 45 as second


-the next two arrays are 10 and 19 as 10 is smaller we take it as first value and 19 as second


-the next two arrays are 55 and 96 as 55 is smaller we take it as first value and 96 as second


-then the merge process repeats we take two arrays[12,23] and [30,45] and compare the first numbers in them as 12 is the smallest, now again comparing the first numbers we get 23 as the second value and 30 and 45 as the third and fourth value


-by taking the next two arrays [10,19] and [55,96] and comparing the first two numbers, 10 is the smallest so we take it as first value, again comparing the first numbers, 19 is the smallest so it is the second value, 55 is the third place and 96 in the fourth


-the merging process repeats again comparing the final two arrays [12,23,30,45] and [10,19,55,96] by comparing the first numbers, 10 is the smallest so it comes as first value, again comparing the first numbers, 12 is the smallest it comes as second value, by comparing the first numbers again and again, we get the list in ascending order [10,12,19,23,30,45,55,96]


-Stop



Algorithm
A   initialization:
                input Array'a' of size 'n' and number of rotations 'd'.
                create an empty array ;rotatedArray; of size'n'
B  calculate effective rotations:
                set 'd' to 'd % n' to handle cases where 'd' is greater than 'n'.
C  shift element :
                 for each index 'i' from '0' to 'n-1':
                 compute the new index as '( i+ n-d) % n'.
                 place the element 'a[i]' at the new index in 'rotatedArray'.
D Return result:
           return the 'rotatedArray'

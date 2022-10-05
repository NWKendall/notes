<h1>Algorithms | Week 3</h1> 
<h3>05/10/2022</h3>

- n[0] = beginning of array
- n[-1] = end of array
- design
    - memory
    - speed
    - correctness - does it work
    - effeciency
        - running time
            - way of describing best and worst case scenarios of algorithm execution
        - Big O notation - upper steps/boundary an algo might take)
            - slowest to fastest
                - O(n2)
                - O(n log n)
                - O(n)
                - O(log n) - divindg n in half
                - O(1) - constant time
        - Big Omega - describes lower bound
        - Big Theta - if Big O and Omega are the same
- C stores data only in arrays, no objects
- objects diffrent from arrays as they also store function (in addition to data)
- selection sort = repeatedly comparing nth value to others to find smallest element then swapping, incrementing location
    - O(n2)
    - omega = n2
    - theta = n2
- bubble sort = comparing adjacent values and smapping accordingly
    - O(n2)
    - Omega = n
- recursion
    - technique a function calls itself
    - base case = condition that protects from infinite loops
- merge sort
    - sort left
    - sort right
    - merge sorted halves
        - compare first elements of each halves


merge > selection > bubble
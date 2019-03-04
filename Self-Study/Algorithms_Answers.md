Add your answers to the Algorithms exercises here.

Exercise I
    a) O(n) because you start with n^2 to get to n^3
    b) O(n^4) because of the 4 nested for loops
    c) O(n) because there is no iteration, just 1 comparison per bunny

Exercise II
    O(logn) because the recursive midpoints means that it won't have to iterate over every floor.

    eggDrop([0 to n]):
        if n is 1 or 0: 
        return n
        
        f = midpoint of array

        if egg breaks at f:
        eggDrop([0 to f])

        if egg doesn't break at f:
        eggDrop([f to n])

        when you array range is [f-1, f, f+1] then you've found f
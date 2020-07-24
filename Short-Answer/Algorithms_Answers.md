#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n)


b) O(n * log(n)) = O(nlog(n))


c) O(1^n)

## Exercise II

def egg_apocalypse(n, start=None, end=None):
    if start and end are None
        # assign 0 to start
        # assign n to end
    # current floor = start + high - low // 2 (midpoint)
    # drop egg at current floor
    # if egg drop on current floor returns broken
        # if egg drop on current floor - 1 returns not broken
            # return current floor <-- Base Case
        # else
            # call egg_apocalypse, start is start and end is current floor
    # else
        # if egg drop on current floor + 1 returns broken
            # return current egg + 1
        # else
            # call egg_apocalypse start is current floor and end is end


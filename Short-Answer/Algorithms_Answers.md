#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) While 'j' is less than 'n', 'j' will double in value and I will
   increment sum by 1. Assuming we start at 0, the while loop will
   return false as such, while j(1) < n(0): # is false.

b) 0(n) because on line 19 while j (1) < n (0) returns false

c) It is doing a recursion that calls itself once per loop; however,
   as a parameter it will deduct userinput, 'bunnies', by 1 until 0
   is reached, otherwise 0(n).

## Exercise II

def checkTheEggs(nStories, eggs):
    breakThreshold = 6
    for story in nStories:
        drop egg from story starting from first story
        if story => breakThreshold:
            return "Eggs broke on story: " + story
         else:
            print("no eggs broken")


Time complexity of this possible solution would be at 6(n)
since on that is the floor eggs would break.


# Title

Mean

# Metadata

## Type

puzzle

# Main Version

## Statement

The average (mean) of 16 different positive integers is 16. What is the greatest possible value that any of these integers could have?

## Correct Answer

136

## Hint

Make the first 15 (different) numbers as small as possible. What does this tell us about the 16th number?

## Explanation

If the mean of 16 numbers is 16, then the total of all the numbers is 16×16 = 256. We want to make one of the numbers as big as possible, so we should make the other 15 numbers as small as possible. The integers have to be different so we should choose 1, 2, 3, ..., 15. If you add them up this gives 120 (a quick way to do it is ½×15×16 = 120). So the biggest number is 256 - 120 = 136.

# Extension 1

## Statement

The average (mean) age of 7 people is 16. Given that all their ages are different positive integers, what is the maximum number of people that could be older than 16?

## Hint

Could everyone be older than 16? If not, can you try and find the maximum number of people that could be older than 16 if just one of the people is as young as possible?

## Correct Answer

5

## Explanation

You cannot make all 7 people older than 16 because the average is 16. You could start with the youngest person being 1, and try to make the other 6 people older than 16 but the total must be 7×16 = 112. With this strategy, 112 - 1 = 111 and 16 + 17 + 18 + 19 + 20 + 21 = 111 so this only gives 5 people older than 16 as you can't count 16 itself. This shows that you cannot do it with 6 people older than 16, but because you have a possibility with 5, this is the largest number you can have. 

# Extension 2 

## Statement

There are some people in the room. When Albert entered the room, the average age increased by 4 years. When Belinda then entered the room, the average age increased by another 3 years. Albert and Belinda are twins. How many people were in the room before Albert entered?

## Hint

Think about Albert giving 4 years to all the people in the room and Belinda giving 3 years to everyone (including Albert).

## Correct Answer

6

## Explanation

There are different ways to solve this puzzle. For each method let n be the number of people in the room.

If Albert and Belinda walked in together, between them they would have added (n + 2)×7 onto the total of all the ages in the room. If just Albert walked in, then he would have added (n + 1)×4 to the total. It is the same for Belinda, so if they both walked in together it would be double this amount. So  (n + 2)×7 = 2×(n + 1)×4. Solving this gives n = 6.

Alternatively, let a be Albert and Belinda's age. The new mean after Albert walks in is (a - 4×n) because Albert has shared out 4 years to everyone in the room to make his age the same. After Belinda walks in the mean is (a - 3×(n + 1)) because she has given 3 years to everyone in the room including Albert. We know that this second expression must be 3 more than the first expression as the mean increased by 3 when Belinda walked in. So we can solve (a - 3×(n + 1)) = a - 4×n + 3  which gives n = 6.

Here is another way. Let the original mean be m. The sum of all the ages is originally (m×n). Let Albert's age be a. When Albert walks in, the new mean is (m + 4). This must be equal to (m×n + a) ∕ (n + 1). When Belinda walks in the room, the new mean is (m + 7). This must be equal to (m×n + 2×a) ∕ (n + 2). Rearranging these equations gives 

m×n + a = m×n + m + 4×n + 4

and

m×n + 2×a = m×n + 2×m + 7×n + 14

Which simplify to

a = m + 4×n + 4 and 2×a = 2×m + 7×n + 14. 

Multiplying the first equation by 2 and subtracting the second one gives n = 6. So there are 6 people in the room at the start. 

# Additional information

## About

The mean is one way of describing a whole set of data with just one number. The median is another way describing the set of data with one number. If the puzzle had asked "The median of 16 different positive integers is 16. What is the greatest possible value that any of these integers could have?", then there would be no solution as you could choose any number as large as you like for the biggest number, as the value of the median of 16 numbers depends only on the eight and ninth biggest numbers! 

## References

* https://www.mathsisfun.com/mean.html

* https://www.mathsisfun.com/median.html


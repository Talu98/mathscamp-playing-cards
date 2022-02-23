# Title

Shuffling Cards

# Metadata

## Type

fun fact

# Main Version

## Statement

If you shuffle a deck of cards properly, it's more than likely that the exact order of the cards you get has never been seen before in the whole history of the universe.

## Hint

How many arrangements of the 52 cards can we have? Maybe this is too big to start with. Let's try out a smaller number of 3 cards, how many different arrangements can we have? Now try 4 cards?

Can we now use this to get to the 52 cards?

## Explanation

We want to work out how many different combinations of 52 cards there are. Let us start with thinking about just 3 cards. We could compare this to thinking about the number of ways 3 people could sit in three numbered chairs. Any of the three people could sit on the first chair, then either of the 2 remaining people could sit on the second chair and then there is 1 person left who would have no choice but to sit on the only remaining chair. We can multiply the number of choices for each chair (3×2×1 = 6) to find how many different ways there are for the 3 people to be arranged. It is interesting to note that the pattern here is taking the initial number then multiplying consecutively by the next smallest integer until you reach 1. This process has a name, it is called **Factorial**. The symbol for it is !. e.g. 3! = 6. Generally if you want to find the number of different ways you can rearrange n items, you can find n! = n!×(n - 1)!×(n - 2)!×…×1 The number of ways to shuffle 52 cards is 52! = 52×51×50×…×3×2×1 which is roughly equal to  8×10⁶⁷

# Extension 1

## Statement

Take a deck of 52 cards, shuffle them as much as you can, then try to guess which exact cards will be the top 3 cards (in order). Did you get your guess right? 

Now if we assume that there are 1 million people doing exactly this procedure, how many would we expect to guess correctly?

## Hint

What is the chance of guessing the top card correctly?

## Explanation

The chance of guessing the first card is 1 ∕ 52. The chance of then getting the second card right is 1 ∕ 51 and then 1 ∕ 50 for the third card. So the chance of guessing all three correctly is (1 ∕ 52)×(1 ∕ 51)×(1 ∕ 50) = 0.0000075415. Multiply this by the 1000000 people guessing gives you 7.51478.. So you would only expect around 7 people to guess correctly.

# Additional information

## About

52! is around 8×10⁶⁷. If someone shuffled a deck of cards once per second since the beginning of the universe (let's say around 14 billion years ago) they would only have shuffled the deck 10¹⁸ times.

Therefore when you shuffle a deck, it is almost certain that you are the first person to play with the cards in exactly that order.

## References

* https://nrich.maths.org/5402

* https://math.hmc.edu/funfacts/making-history-by-card-shuffling/


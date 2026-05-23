Binary Search Guessing Game

I built this to visualize one of the most satisfying algorithms in computer science. Binary search is something every CS student learns early on, 
but seeing it actually work in real time — watching it cut the search space in half with every single guess — hits different when it's interactive.

What it does
The AI guesses any number between 1 and 100 in at most 7 tries. Every time it guesses, it eliminates half the remaining possibilities based on your feedback. It never loses, and it never needs more than 7 guesses 
that's the beauty of O(log n).

Why it matters beyond the game
Binary search isn't just a guessing game trick. It's the foundation behind database indexing, search trees, and efficient data retrieval in real systems. Building this was my way of making that connection concrete.

What I learned
Implementing divide and conquer logic from scratch
Visualizing algorithm steps in a way that's easy to follow
How logarithmic time complexity plays out in practice

play here:https://hadialafyouni.github.io/binary-search-ai/

Built with
HTML · CSS · JavaScript

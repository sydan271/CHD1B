
# B. Destined Pebbles

> People say that sometimes, connections don’t need traits or bonds to be made – sometimes, just a few pebbles are enough. – Tố-chém-dậy, a famous philosopher from the 22nd century

If you have a passion for classic problems, the T-s-x game has become legendary. It all began from that fateful day when Thanh discovered the joy of life: MNF...

One day, on a sunny afternoon, Thanh and Minh met in the garden near the General University dorm. It was a place full of students. They were bored and wanted to play something. Thanh picked up two piles of pebbles from the garden corners and challenged Minh to a mental duel. Of course, a bet was involved – the loser had to reveal a big personal secret.

### Game Rules:

There are two piles of pebbles: the first pile has **A** pebbles, and the second pile has **B** pebbles (where 0 < A, B ≤ 10⁹, and A ≠ B > 0). Thanh and Minh take turns making moves until only one pebble remains. Thanh always goes first.

In each turn, a player can:

- Remove one pebble from the first pile.
- If the second pile is even, remove half of its pebbles, then throw one of them into the first pile.

The game ends when only one pebble remains. If the last remaining pebble is in the first pile, Thanh wins; otherwise, Minh wins.

Determine who the winner is if both play optimally.

---

### Input

- The first line contains an integer `T`, the number of test cases.
- Each of the next `T` lines contains two integers `A` and `B`.

---

### Output

For each test case, output `"Thanh"` if Thanh wins or `"Minh 11"` if Minh wins.

---

### Sample

#### Input
```
2
1 2
0 2
```

#### Output
```
Minh 11
Thanh
```

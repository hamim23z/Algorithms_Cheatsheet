```
**Insertion Sort**
- BCRT: O(n)
- ACRT: O(n^2)
- WCRT: O(n^2)

**Merge Sort**
- BCRT: O(nlgn)
- ACRT: O(nlgn)
- WCRT: O(nlgn)

**Heap Sort**
- BCRT: O(nlgn)
- ACRT: O(nlgn)
- WCRT: O(nlgn)
Also for heap sort, the build max heap is O(n) and the heapify call is O(lgn).

**Quick Sort**
- BCRT: O(nlgn)
- ACRT: O(nlgn)
- WCRT: O(n^2)
Also for quick sort, there exists randomized quick sort. And this is chosen more because it lowers the chances of getting
the worst case. So we would ideally use randomized quick sort. 
```
.
.
.
.
```
**Master Theorem Cases**
1. f(n) < nlogba. Then T(n) = Θ(nlogba)
2. f(n) = nlogba. Then T(n) = Θ(nlogba lgn)
3. f(n) > nlogba. And the recurrence relation of af(n/b) <= cf(n) where c<1 holds. Then T(n) = Θ(f(n))
```
.
.
.
.
```
**Notations**
1. Θ Notation. Big Theta. This is 0 <= c1g(n) <= f(n) <= c2g(n). Then it's Θ(g(n)). And this is a tight bound, both upper and lower. 
2. O Notation. Big Oh.    This is 0 <= f(n) <= cg(n). Then it's O(g(n)). And this is an upper bound only. 
3. Ω Notation. Big Omega. This is 0 <= cg(n) <= f(n). Then it's Ω(g(n)). And this is lower bound only. 
```

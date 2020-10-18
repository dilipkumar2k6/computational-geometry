# Summary
https://www.educative.io/courses/grokking-the-coding-interview/3YVYvogqXpA
# 1d interval search
- Instead of point, our data is interval
- Support of following operations
    - insert
    - search for interval
    - delete an interval
    - interval intersection query
![](assets/interval-search.png)
- Use left point of each interval as binary search tree key
- Store max endpoint in subtree rooted at node
# Interval search tree
![](assets/interval-search-tree.png)
# Insert interval
![](assets/insert-interval.png)
# Search interval
- Use case 1
![](assets/search-1.png)
- Use case 2
![](assets/search-2.png)
- Use case 3
![](assets/search-3.png)
- Algorithm
![](assets/search-algo.png)
- Proof 1
![](assets/search-algo-proof-1.png)
- Proof 2
![](assets/search-algo-proof-2.png)
# Time complexity
![](assets/time-complexity.png)
# Orthogonal line segment intersection
![](assets/orthogonal-line-segment-intersection.png)
# Sweep line algo
![](assets/sweep-line-algo.png)
# Sweep line algo analysis
![](assets/sweepline-analysis.png)

# Problems
https://leetcode.com/problems/meeting-rooms/

https://leetcode.com/problems/meeting-rooms-ii/

https://leetcode.com/problems/merge-intervals/

https://leetcode.com/problems/insert-interval/

https://leetcode.com/problems/interval-list-intersections/

https://leetcode.com/problems/employee-free-time/

https://leetcode.com/problems/range-module/

# CMPS 2200 Recitation 05
## Answers

**Name:**_________________________
**Name:**_________________________


Place all written answers from `recitation-05.md` here for easier grading.




- **3)**
The work of get_positions is O(n) because our efficient version of scan from class was O(n). . The span of this is O(log(n)) .


- **5)**
The work of construct_output is O(n) . The span of construct_output is still O(n). Nothing can be parallelized because each loop requires the positions list to be updated. .


- **6)**

The work of count is O(n), the work of get positions is O(n) and the work of construct_output is O(n). This makes the supersort algorithm n + n + n = 3n or O(n). The span is also O(n) because although get_positions is log(n), O(n) asymptotically dominates it.


- **8)**
- The work is still O(n) but now the span is O(log(n))

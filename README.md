# DSA Visualizations

Interactive step-through animations for LeetCode solutions. Each page is a single self-contained HTML file: code panel with synced line highlighting, live data-structure stage, call-stack cards, and Play / Pause / Prev / Next / Reset controls.

Live: **https://kinny94.github.io/dsa-visualizations/**

## Catalog

| # | Problem | Pattern |
|---|---|---|
| [109](https://kinny94.github.io/dsa-visualizations/lc109-sorted-list-to-bst.html) | Convert Sorted List to Binary Search Tree | Recursion / Inorder simulation |
| [427](https://kinny94.github.io/dsa-visualizations/lc427-construct-quad-tree.html) | Construct Quad Tree | Recursion / Divide & Conquer |
| [346](https://kinny94.github.io/dsa-visualizations/lc346-moving-average.html) | Moving Average from Data Stream | Queue · Bounded |
| [239](https://kinny94.github.io/dsa-visualizations/lc239-sliding-window-maximum.html) | Sliding Window Maximum | Queue · Monotonic Deque |
| [155](https://kinny94.github.io/dsa-visualizations/lc155-min-stack.html) | Min Stack | Stack · Two-Stack |
| [496](https://kinny94.github.io/dsa-visualizations/lc496-next-greater-element-i.html) | Next Greater Element I | Stack · Monotonic |
| [141](https://kinny94.github.io/dsa-visualizations/lc141-linked-list-cycle.html) | Linked List Cycle | Linked List · Floyd's |
| [92](https://kinny94.github.io/dsa-visualizations/lc92-reverse-linked-list-ii.html) | Reverse Linked List II | Linked List · Pointer Surgery |
| [654](https://kinny94.github.io/dsa-visualizations/lc654-maximum-binary-tree.html) | Maximum Binary Tree | Stack · Monotonic |
| [78](https://kinny94.github.io/dsa-visualizations/lc78-subsets.html) | Subsets | Recursion · Backtracking |
| [39](https://kinny94.github.io/dsa-visualizations/lc39-combination-sum.html) | Combination Sum | Recursion · Backtracking |
| [40](https://kinny94.github.io/dsa-visualizations/lc40-combination-sum-ii.html) | Combination Sum II | Recursion · Backtracking |
| [90](https://kinny94.github.io/dsa-visualizations/lc90-subsets-ii.html) | Subsets II | Recursion · Backtracking |
| [216](https://kinny94.github.io/dsa-visualizations/lc216-combination-sum-iii.html) | Combination Sum III | Recursion · Backtracking |
| [77](https://kinny94.github.io/dsa-visualizations/lc77-combinations.html) | Combinations | Recursion · Backtracking |
| [46](https://kinny94.github.io/dsa-visualizations/lc46-permutations.html) | Permutations | Recursion · Backtracking |
| [17](https://kinny94.github.io/dsa-visualizations/lc17-letter-combinations-of-phone-number.html) | Letter Combinations of a Phone Number | Recursion · Backtracking |
| [47](https://kinny94.github.io/dsa-visualizations/lc47-permutations-ii.html) | Permutations II | Recursion · Backtracking |
| [22](https://kinny94.github.io/dsa-visualizations/lc22-generate-parentheses.html) | Generate Parentheses | Recursion · Backtracking |
| [131](https://kinny94.github.io/dsa-visualizations/lc131-palindrome-partitioning.html) | Palindrome Partitioning | Recursion · Backtracking |
| [93](https://kinny94.github.io/dsa-visualizations/lc93-restore-ip-addresses.html) | Restore IP Addresses | Recursion · Backtracking |
| [51](https://kinny94.github.io/dsa-visualizations/lc51-n-queens.html) | N-Queens | Recursion · Backtracking |
| [761](https://kinny94.github.io/dsa-visualizations/lc761-special-binary-string.html) | Special Binary String | Recursion · Greedy |
| [980](https://kinny94.github.io/dsa-visualizations/lc980-unique-paths-iii.html) | Unique Paths III | Recursion · Backtracking |
| [301](https://kinny94.github.io/dsa-visualizations/lc301-remove-invalid-parentheses.html) | Remove Invalid Parentheses | Recursion · Backtracking |
| [37](https://kinny94.github.io/dsa-visualizations/lc37-sudoku-solver.html) | Sudoku Solver | Recursion · Backtracking |
| [104](https://kinny94.github.io/dsa-visualizations/lc104-maximum-depth-of-binary-tree.html) | Maximum Depth of Binary Tree | Binary Tree · Recursion |
| [637](https://kinny94.github.io/dsa-visualizations/lc637-average-of-levels-in-binary-tree.html) | Average of Levels in Binary Tree | Binary Tree · BFS |

## Adding a new animation

1. Drop the new HTML in the repo root, named `lc<NUMBER>-<slug>.html`.
2. Add a row to `index.html` and to the table above.
3. Commit and push — GitHub Pages redeploys automatically.

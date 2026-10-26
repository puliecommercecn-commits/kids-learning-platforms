# Kids Learning Platforms

Interactive learning pages for a 6th-grade student, built to open locally
on iPad (no VPN, no login). Each page is a single self-contained HTML file.

## Contents

- `cpp/index.html` — C++ informatics platform, 18 lessons for the school
  semester: trees (concepts/storage, binary trees, traversal, complete
  binary trees, BST, Huffman, Trie, Fenwick tree, comprehensive problems)
  → DP (basics, linear DP: triangle/LIS/LCS, 01 knapsack, complete and
  multiple knapsack, interval DP: stone merging) → graphs (adjacency
  matrix/list, DFS/BFS, topological sort, Floyd/Dijkstra/heap Dijkstra,
  SPFA, Prim/Kruskal).
- `english/index.html` — English weekly-report speaking practice: a
  15-sentence report script with listen buttons, work vocabulary,
  number/date reading, and shadowing recording. Pronunciation
  correction is done by Muse in chat, not by the page.
- `math/index.html` — Shaokeyuan math platform, 3 number theory modules:
  factors/primes/multiples, divisibility/remainders, place value and
  perfect squares. Each module has worked examples, consolidation
  exercises with worked solutions, and a final test section.

## Updating

New handouts or problem sets are added incrementally to the existing
structure (one commit per update). The exported HTML files are the
deliverables; the hosted artifact links are not the iPad route.

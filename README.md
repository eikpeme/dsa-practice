# Data Structures & Algorithms (DSA) Practice

## 📌 **Overview**
This repository tracks our **DSA learning journey**, with solutions to common algorithm problems categorized by topic. Each solution includes an **explanation**, **approach**, and **complexity analysis**.

## 📅 **Study Plan & Topics**

### **Week 1: Arrays, Hashing & Two Pointers**
- [ ] [Two Sum](https://leetcode.com/problems/two-sum/)
- [ ] [Valid Anagram](https://leetcode.com/problems/valid-anagram/)
- [ ] [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/)
- [ ] [Container With Most Water](https://leetcode.com/problems/container-with-most-water/)

### **Week 2: Stacks, Queues & Fast/Slow Pointers**
- [ ] [Valid Parentheses](https://leetcode.com/problems/valid-parentheses/)
- [ ] [Min Stack](https://leetcode.com/problems/min-stack/)
- [ ] [Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/)

### **Week 3: Binary Search & Sorting**
- [ ] [Binary Search](https://leetcode.com/problems/binary-search/)
- [ ] [Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/)
- [ ] [Kth Largest Element](https://leetcode.com/problems/kth-largest-element-in-an-array/)

### **Week 4: Recursion, Backtracking & DFS/BFS**
- [ ] [Generate Parentheses](https://leetcode.com/problems/generate-parentheses/)
- [ ] [Word Search](https://leetcode.com/problems/word-search/)
- [ ] [Number of Islands](https://leetcode.com/problems/number-of-islands/)

### **Week 5: Dynamic Programming & Greedy Algorithms**
- [ ] [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/)
- [ ] [House Robber](https://leetcode.com/problems/house-robber/)
- [ ] [Coin Change](https://leetcode.com/problems/coin-change/)

### **Week 6: Graphs & System Design**
- [ ] [Graph Valid Tree](https://leetcode.com/problems/graph-valid-tree/)
- [ ] [Course Schedule](https://leetcode.com/problems/course-schedule/)
- [ ] [Dijkstra’s Shortest Path](https://leetcode.com/problems/network-delay-time/)

## 📂 **Folder Structure**
```plaintext
/dsa-practice
  ├── arrays/
  │   ├── two-sum.ts
  │   ├── sliding-window-max.ts
  ├── graphs/
  │   ├── dijkstra.ts
  │   ├── topological-sort.ts
  ├── dynamic-programming/
  │   ├── house-robber.ts
  │   ├── coin-change.ts
  ├── .github/workflows/
  │   ├── lint.yml
  │   ├── test.yml
  ├── README.md (this file)
```

## 🛠 **How to Contribute**
1. Clone the repo
   ```bash
   git clone https://github.com/yourusername/dsa-practice.git
   ```
2. Create a new branch for a problem
   ```bash
   git checkout -b feature/two-sum
   ```
3. Implement the solution & add explanations
4. Commit and push the branch
   ```bash
   git push origin feature/two-sum
   ```
5. Open a Pull Request (PR) for review

## 🚀 **GitHub Workflows**
This repo includes automated workflows:
- **Linting:** Ensures code follows best practices using ESLint.
- **Testing:** Runs test cases to verify correctness.

### **Setting Up Workflows**
1. **Linting (`.github/workflows/lint.yml`)**
```yaml
name: Lint Code
on: [push, pull_request]
jobs:
  lint:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: actions/setup-node@v3
        with:
          node-version: '18'
      - run: npm install
      - run: npm run lint
```

2. **Testing (`.github/workflows/test.yml`)**
```yaml
name: Run Tests
on: [push, pull_request]
jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: actions/setup-node@v3
        with:
          node-version: '18'
      - run: npm install
      - run: npm test
```

## 📚 **Resources**
- [LeetCode](https://leetcode.com/)
- [NeetCode.io](https://neetcode.io/)
- [Tech Interview Handbook](https://www.techinterviewhandbook.org/)



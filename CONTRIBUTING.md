# Contributing & Naming Conventions

Thanks for visiting — here’s how this repo is organized and how to add new problems.

Repository conventions
- Topic folders: snake_case or kebab-case (e.g., arrays, dynamic_programming)
- Problem folder: include a short, unique identifier or leetcode/gfg id if available, e.g.:
  - 1_two_sum
  - 21_merge_two_sorted_lists
  - longest_substring_without_repeating_chars (if no id)
- Inside each problem folder:
  - README.md — problem statement, intuition, approach summary, complexity
  - Solution.java — Java implementations with both brute and optimal versions
  - Optionally: test_input.txt, sample_output.txt

README.md format (required)
- Title (problem name + id)
- Problem (short copy or link)
- Intuition (1–3 paragraphs)
- Approach (brief steps)
- Complexity (Time: , Space: )

Solution.java format (required)
- Header comment with problem name and link
- Two classes/methods or clearly separated sections:
  - BruteForce approach (commented)
  - Optimal approach (commented)
- Main method with example input + instructions to run

PRs & Code Style
- Use camelCase for method and variable names
- Keep single-file solutions under ~200 lines if possible
- Add comments explaining tricky parts

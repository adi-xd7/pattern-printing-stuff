INSTRUCTIONS

## What You'll Learn

This assignment is designed to teach you multiple skills beyond just coding patterns:

- **Pattern Logic & Problem Solving**: Implement 15 different pattern-printing problems ranging from basic to advanced (nested loops, symmetry, number sequences).
- **C++ Programming**: Practice writing clean, readable C++ code with proper formatting and comments.
- **Git & GitHub Workflow**: Learn how to fork a repository, create branches, commit changes, and push to your fork.
- **Pull Requests (PRs)**: Understand how to open a PR and write clear descriptions.
- **Open Source Contribution**: Experience the real-world workflow used in open-source projects worldwide.

This is a hands-on way to build both your coding and collaboration skills!

---

## Step 1: Fork the Repository

1. Go to the repository: `https://github.com/aviraltrip/pattern-printing-stuff`
2. Click the **Fork** button in the top-right corner to create a copy of the repository under your GitHub account.
3. Clone your forked repository to your local machine:
   ```bash
   git clone https://github.com/<your-username>/pattern-printing-stuff.git
   cd pattern-printing-stuff
   ```
4. Add the original repository as an upstream remote (to sync updates later):
   ```bash
   git remote add upstream https://github.com/aviraltrip/pattern-printing-stuff.git
   ```

## Step 2: Create Your Directory

1. Create your own directory at the repository root named with your GitHub username (or your name).
   - Example: `your-name/`

## Step 3: Add Your Pattern Solutions

1. Inside your directory add one C++ file per pattern you implement.
   - Use the pattern number from `README.md` as a prefix and a short descriptive name,
    
    e.g. : `pattern01.cpp`

   - Each file must contain a `main()` that reads the input number exactly as shown in `README.md` and prints the expected pattern to stdout.
   - At the top of each file include a short comment with the sample input and expected output.

## Step 4: Coding Guidelines

   - Use standard C++.
   - No external libraries required.
   - Keep code readable and well-formatted. Add brief comments where logic is non-obvious.
   - Handle the input constraints assumed in the pattern (reasonable n values). No need for heavy optimization.

## Step 5: Build and Run Locally

   - Compile:
     ```bash
     g++ pattern01.cpp
     ```
   - Run (example):
     ```bash
     ./a.out (for UNIX based) 
     ./a.exe (for windows)
     ```

## Step 6: Commit and Push to Your Fork

1. Create a branch from `main` named like:
   - `add/<your-username>-patterns` or `feature/<your-username>/patterns`
   ```bash
   git checkout -b add/<your-username>-patterns
   ```

2. Add and commit your files under your directory:
   ```bash
   git add <your-name>/
   git commit -m "Add pattern solutions by <your-name>"
   ```

3. Push the branch to your forked repository:
   ```bash
   git push origin add/<your-username>-patterns
   ```

## Step 7: Open a Pull Request

1. Go to your forked repository on GitHub: `https://github.com/<your-username>/pattern-printing-stuff`
2. You'll see a prompt to **Compare & pull request** for your recently pushed branch. Click it.
3. Ensure the base repository is `aviraltrip/pattern-printing-stuff` and base branch is `main`.
4. Set a clear PR title, e.g., `Add pattern solutions — <your-name>`.
5. In the PR description, list which pattern numbers you implemented and any notes (optional).
6. Click **Create pull request**.

---

Fork the repo, create your directory, add C++ solutions for the patterns from `README.md`, and open a PR!
# How to Push Code to GitHub with Merge Requests

Follow these steps to work with branches and pull requests in the repository  
**https://github.com/maryblack/online-market-discovery/**

---

## ✅ Step 1: Clone the repository

```bash
git clone https://github.com/maryblack/online-market-discovery.git
cd online-market-discovery
```

---

## ✅ Step 2: Create a new branch

Always work in a branch. Never push directly to `main`.

```bash
git checkout -b feature/your-branch-name
```

---

## ✅ Step 3: Make your changes

Add files to the folder with your county ISO code, edit or delete files as needed.

---

## ✅ Step 4: Check status

See what’s changed.

```bash
git status
```

---

## ✅ Step 5: Stage your changes

Add all files:
```bash
git add .
```

Or add specific files (this is preferable option):
```bash
git add file1.py file2.py
```

---

## ✅ Step 6: Commit your changes

Write a commit message:

```bash
git commit -m "EDA analysis notebook for ES"
```

---

## ✅ Step 7: Push your branch to GitHub

```bash
git push origin feature/your-branch-name
```

---

## ✅ Step 8: Create a Pull Request (Merge Request)

1. Go to [your repo](https://github.com/maryblack/online-market-discovery).
2. Click the **“Compare & pull request”** button, or go to the **Pull requests** tab → **New pull request**.
3. Make sure:
   - **Base branch:** `main`
   - **Compare branch:** your new branch (e.g., `feature/your-branch-name`)
4. Add a title and description.
5. Click **“Create pull request”**.

---

## ✅ Step 9: Review & Merge

- Review the changes and wait for approval.
- Click **“Merge pull request”** when ready.
- Delete the branch if it’s no longer needed.

---

## 🗃️ Extra Tips

- Always pull the latest changes before starting new work:
  ```bash
  git checkout main
  git pull origin main
  ```

---


## 🧭 GitHub Expert Sprint – Day 1 Journal
**Date:** Nov 9, 2025  
**Theme:** Core Git & Collaboration Foundations  
**Duration:** ~6 hours  

---

### 🧠 What I Learned
1. **Git vs GitHub:** Git is the local version-control engine; GitHub is the collaborative cloud interface.  
2. **Repository Lifecycle:** `git init → add → commit → push` creates a complete local-to-remote workflow.  
3. **Branching Concept:** Branches are lightweight pointers – no new folders, just alternate timelines of commits.  
4. **Pull Requests:** A PR is a formal proposal on GitHub to merge one branch into another, enabling review and collaboration.  
5. **Clean-Up Discipline:** Deleting merged branches (remote & local) keeps history tidy.  
6. **Authentication Basics:** OAuth / PATs secure push access and are stored via Git Credential Manager.  

---

### ⚙️ Commands Practiced
```
git init
git add .
git commit -m "Initial commit"
git remote add origin <url>
git push -u origin main
git branch feature-readme-update
git checkout feature-readme-update
git merge feature-readme-update
git branch -a
git branch -d feature-readme-update
```

---

### 📚 Concepts Mastered
| Area | Skill Level |
|------|-------------|
| Local Git Setup | ✅ Confident |
| Commits & Staging | ✅ Confident |
| Branching & Merging | ✅ Confident |
| Pull Requests | ✅ Operational |
| Authentication | ✅ Configured |
| Cleanup & Branch Tracking | ✅ Practiced |

---

### 💡 Key Takeaways
- *Git doesn’t create folders per branch; it time-travels file versions.*  
- *Use `git push -u origin <branch>` once, then just `git push`.*  
- *A Pull Request is conversation + merge, not a Git command.*  
- *Deleting stale branches keeps your repo lean.*  

---

### 🌙 End-of-Day Reflection
> “Today, I stopped copying commands and started *understanding* them.”  
> – Vikram Arcot-Vantel, Day 1 of the GitHub Expert Sprint  

---

### 🔜 Next Session Preview (Day 2)
🧩 Phase 4 – GitHub Actions & Automation  
- Set up a YAML workflow file  
- Automate formatting or test checks  
- Trigger CI/CD on every push  

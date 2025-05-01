# Git-Test DAY 1
Git & Github
1.	Project doc
2.	Project doc 2
3.	Project doc v5

VCS - Version Control System

1. Portfolio (.html) - 
    1. commit -m "Initial Commit" - save current state as snapshot (timestamp) gives a unique id
    2. commit -m "Add skill section" - current  (-m: message)


CORE Concepts:

1. Repository: (online)

2. Working directory: (offline)
    
3. Staging Area (offline)


Commands
1.	Git clone
2.	Git add filename
3.	Git commit
4.	Git push


DAY 2
Benefits
Trunk-Based Development (TBD)
•	Faster feedback: Since everyone is merging to the same branch, integration issues are detected earlier.
•	Simpler structure: No need for complex branching strategies or long-lived branches.
•	Continuous delivery: Easier to maintain a continuous flow to production with frequent merges.
•	Improved collaboration: Developers work on the same branch, making it easier to share and collaborate on changes.
•	Less merge conflict: Frequent small merges minimize the chances of conflicts, as they are easier to resolve in small batches.

Branch-Based Development (BBD)
•	Isolation: Developers can work independently on feature branches without interfering with others.
•	Better for complex features: Features can be developed and tested independently of the main branch.
•	Clear version control: Easier to track development of specific features or versions.
•	Safer for large teams: Allows developers to work on features without the constant pressure of integrating into a single branch.

Challenges

Trunk-Based Development (TBD)
•	Requires strong CI/CD: Frequent merging into the main branch demands continuous integration and automated testing to ensure stability.
•	Feature flag complexity: Managing unfinished features with feature flags can add complexity.
•	High discipline required: Developers must commit often and ensure their code works well with others.
•	Risk of breaking main: If not well-managed, frequent commits to main might risk breaking the build.

Branch-Based Development (BBD)
•	Merge conflicts: Long-lived branches may cause more merge conflicts, especially if many developers are working on different branches for an extended period.
•	Slower integration: Merging features back into the main branch can be time-consuming, and features might get outdated before merging.
•	Harder to maintain: Multiple long-lived branches can become difficult to manage, especially if they fall behind main.
•	Delayed feedback: Delays in merging code can lead to integration problems that aren't discovered until later.


Imp Stapes: 
git config --global user.name "Your Name" 
git config --global user.email "your_email@example.com" 
git init git remote add origin https://github.com/imam-nadaf/softcraft01 
git clone https://github.com/imam-nadaf/softcraft01 
cd C:\Users\imam\softcraft01
git add README.md 
git commit -m "Add README.md" 
git push -u origin main

# 2023. 12. 22.



# A: Git Branching and Collaboration Workflow

1. When assigned a task, create a post on the issue tracker.
2. Create a feature branch and proceed with development there.
3. When committing, adhere to the convention for writing messages and include the issue number.
5. Upon completing development, open a Pull Request from the feature branch to the develop branch for merging.
6. Other team members will review the code. -> Always leave one or more comments to confirm that you have reviewed the code.
7. Once the review is complete, proceed with the merge.


# B: Commit message convention
## 1. Commit Message Structure
```
(emoji) Commit Type: subject (#issueNumber)
	(empty line)
body
	(empty line)
footer
```
**If the content is minimal, only the title will be provided.**

## 2. Commit Type
* ✨ Feat: Adding new features
* 🐛 Fix: Bug fixes
* 📚 Docs: Documentation updates
* 💄 Style: When improving UI / Code style
* 🔨 Refactor: Code refactoring

## 3. Example
```
✨Feat: 간편결제 UI design (#23)

1.tableView 
2.scroll to top method

Ref: #001	=>	(footer)
```


# C: Deployment Guidelines
1. If the app review is successful and deployment is underway, make sure to merge from the develop branch to the main branch, including a version tag.
2. Please delete any legacy branches associated with this deploymen




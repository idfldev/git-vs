
### === Base git commands for tutorial ===

- git init -> first command in the folder
- git add filename
- git status

- git config --global user.email "<you@example.com>"
- git config --global user.name "Your Name"

- git checkout -b new_branch_name
- git add .
- git merge master
- git checkout master

#### …or create a new repository on the command line echo "# test_git" >> README.md*

- git init
- git add README.md
- git commit -m "first commit"
- git branch -M master
- git remote add origin <https://github.com/idfldev/test_git.git>
- git push -u origin master
- git pull origin master

#### …or push an existing repository from the command line*

- git remote add origin <https://github.com/idfldev/test_git.git>
- git branch -M master
- git push -u origin master

### ==== Here's a list of common Git commands for beginners to advanced users: ===

- Basic Git Commands:
  - **git init**: Initialize a new Git repository in the current directory.
  - **git clone [repository_url]**: Clone a remote repository to your local machine.
  - **git add [file]**: Stage changes for commit. You can also use git add . to stage all changes.
  - **git commit -m "message"**: Commit staged changes with a descriptive message.
  - **git status**: Check the status of your working directory and staged changes.
  - **git log**: View the commit history.
  - **git diff**: Show the differences between the working directory and the last commit.
  - **git branch**: List all branches in your repository.
  - **git branch [branch_name]**: Create a new branch.
  - **git checkout [branch_name]**: Switch to a different branch.
  - **git merge [branch_name]**: Merge changes from one branch into the current branch.
  - **git pull**: Fetch and merge changes from a remote repository.
  - **git push**: Push your local commits to a remote repository.

- Intermediate Git Commands:
  - **git remote**: List remote repositories.
  - **git remote add [name] [repository_url]**: Add a remote repository.
  - **git fetch [remote]**: Fetch changes from a remote repository.
  - **git branch -d [branch_name]**: Delete a local branch.
  - **git push [remote] --delete [branch_name]**: Delete a remote branch.
  - **git tag [tag_name]**: Create a lightweight tag at the current commit.
  - **git tag -a [tag_name] -m "message"**: Create an annotated tag.
  - **git diff [commit1] [commit2]**: Show differences between two commits.
  - **git stash**: Temporarily save changes that are not ready to be committed.
  - **git stash apply**: Apply the most recent stash.
  - **git reset [commit]**: Unstage changes and move the branch pointer.
  - **git rebase [branch_name]**: Reapply your changes on top of another branch.
  - **git cherry-pick [commit]**: Apply a specific commit from one branch to another.

- Advanced Git Commands:
  - **git bisect**: Find a specific commit that introduced a bug.
  - **git reflog**: View a log of all Git references.
  - **git submodule**: Manage submodules within your repository.
  - **git filter-branch**: Rewrite history by applying custom filters.
  - **git blame [file]**: Show who last modified each line of a file.
  - **git cherry**: List commits not yet applied to another branch.
  - **git worktree**: Manage multiple working trees for the same repository.
  - **git gc**: Garbage collect and optimize the Git repository.
  - **git fsck**: Check the integrity of your Git database.
  
>These are some of the most commonly used Git commands. Keep in mind that Git is a powerful version control system,
>and there are many more commands and options available. You can use git --help followed by a command to get detailed
>information about its usage. Additionally, the Git documentation and various
>online tutorials can help you learn more about using Git effectively.

### === How To Markdown Format in Readme.md File ===

Formatting files using Markdown is a common practice,
especially when creating README.md files for projects
on platforms like GitHub. Markdown is a lightweight markup
language that allows you to format text documents with ease.
Below is a list of common Markdown formatting elements that
you can use in a README.md file or any Markdown document:

- Headers:

```markdown
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6
```

- Emphasis:

```markdown
*Italic* or _Italic_
**Bold** or __Bold__
```

- Lists:
  - Unordered List:

```markdown
- Item 1
- Item 2
  - Subitem 1
  - Subitem 2
```

1. Ordered List:

```markdown
1. First item
2. Second item
```

- Links:

```markdown
[Link Text](URL)
```

- Images:

```markdown
![Alt Text](Image_URL)
```

- Blockquotes:

```markdown
> This is a blockquote.
```

- Code:
  - Inline code:

```python
Use backticks (`) to highlight `inline code`.
```

- Code block:
  - Python
  - markdown

```python
def hello_world():
    print("Hello, World!")
```

> Specify the language after the triple backticks to enable syntax highlighting for that language.

- Tables:

```markdown
| Header 1  | Header 2  |
| --------- | --------- |
| Content 1 | Content 2 |
```

- Task Lists:

```markdown
- [x] Completed task
- [ ] Incomplete task
```

- Links to Sections in the Document:

```markdown
[Link to Header](#header-1)
```

- Replace header-1 with the actual identifier of your header.
  - Escaping Characters:

> If you want to display a Markdown character as-is (without formatting), you can escape it using a backslash (\). For example, to display an asterisk as an asterisk and not as an emphasis marker:

```markdown
\*This will not be italicized\*
```

- Horizontal Rule:

> Markdown interprets three or more hyphens, asterisks, or underscores as a horizontal rule:

```markdown
---
***
___
```

> These are the most commonly used Markdown formatting elements for
> creating README.md files and other Markdown documents.
> You can combine and customize these elements to
> suit your specific documentation needs.

- Footnotes:

```markdown
H~2~O is a liquid. E=mc^2^ is an equation.
```

> Use ~ for subscript and ^ for superscript.
> These Markdown formatting elements can help you create well-structured and visually appealing content for webpages.
> You can mix and match these elements to suit your specific needs and create informative and engaging web content.

1\. Git hooks stored in `.git/hooks` are local to each clone and are not shared through `git push`.

2\. Teams can share hooks by storing scripts in a tracked `.githooks` folder.

3\. Each team member can activate them using `git config core.hooksPath .githooks`.

4\. This allows consistent commit validation across the team.

5\. Using `git commit --no-verify` bypasses certain hooks and may allow invalid commits.


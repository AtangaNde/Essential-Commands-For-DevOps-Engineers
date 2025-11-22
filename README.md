# Essential-Commands-For-DevOps-Engineers

## LINUX COMMANDS

1.uname -a – Show system information

2.uptime – Show system uptime

3.hostname – Show hostname

4.whoami – Show current user

5.ls -lah – List directory contents with permissions

6.pwd – Show current directory

7.cd /path – Change directory

8.mkdir -p /path – Create a directory (with parent

if needed)

9.rm -rf /path – Remove directory recursively

10. cp -r source target – Copy files/directories
recursively

11. mv oldname newname – Move/Rename file

12. ps aux – Show running processes

13. top – Show real-time system performance

14. kill -9 PID – Kill a process forcefully

15. pkill -f process_name – Kill process by name

16. df -h – Show disk space usage

17. du -sh /path – Show directory size

18. netstat -tulnp – Show listening ports

19. ss -tulnp – Show listening ports (alternative)

20. who – Show logged-in users

21. adduser username – Create a new user

22. passwd username – Change user password

23. usermod -aG group user – Add user to a group

24. grep "text" file.txt – Search for a string in a
file

25. find /path -name "*.log" – Find files matching
pattern

26. chmod 755 file.sh – Change file permissions

27. chown user:group file – Change file owner

28. tar -czf archive.tar.gz directory/ – Compress
files

29. tar -xzf archive.tar.gz – Extract compressed file

30. cat file.txt – View file contents

31. tail -f /var/log/syslog – View real-time log
updates

32. echo "text" >> file.txt – Append text to file

33. history – Show command history

34. clear – Clear terminal screen

35. alias ll='ls -lah' – Create an alias

36. df -Th – Show file system disk space

37. wc -l file.txt – Count number of lines in a file

38. cut -d':' -f1 /etc/passwd – Extract first column
from file

39. awk '{print $1}' file.txt – Print first column of
Text

40. sed -i 's/old/new/g' file.txt – Replace text in a
file

41. crontab -e – Edit cron jobs

42. cron -l – List scheduled cron jobs

43. rsync -av source/ target/ – Sync files

44. scp user@host:/path/to/file . – Secure copy file

45. ssh user@host – SSH into a server

46. exit – Logout from shell

47. uptime – Show system uptime

48. free -m – Show memory usage

49. top – Show system performance

50. vmstat – Show CPU/memory status

## GIT COMMANDS 

52. git init – Initialize a git repository

53. git clone repo_url – Clone a repository

54. git status – Show changes

55. git add . – Stage all changes

56. git commit -m "msg" – Commit changes

57. git push origin branch – Push changes

58. git pull origin branch – Pull latest changes

59. git checkout branch – Switch branch

60. git branch -a – List all branches

61. git merge branch – Merge branch into current
branch

62. git log --oneline – Show commit history

63. git diff – Show changes

64. git stash – Stash changes

65. git stash pop – Apply stashed changes

66. git reset --hard HEAD~1 – Reset last commit

67. git revert commit_id – Revert commit

68. git tag -a v1.0 -m "Version 1.0" – Create tag

69. git push --tags – Push tags

70. git rm file – Remove a file from git

71. git clean -fd – Remove untracked files

72. git config --global user.name "Your Name" – Set
global username

73. git config --global user.email "you@example.com"
– Set global email

74. git show commit_id – Show commit details

75. git blame file.txt – Show changes by line

76. git remote -v – Show remote repositories

77. git remote add origin URL – Add remote repo

78. git rebase branch – Rebase branch

79. git cherry-pick commit_id – Pick specific commit

80. git fetch – Fetch remote changes

81. git log --graph – Show graphical commit log

82. git branch -d branch_name – Delete branch

83. git pull --rebase – Rebase while pulling

84. git push --force – Force push changes

85. git reflog – Show reflog

86. git diff HEAD~1 – Show last commit changes

87. git apply patch.diff – Apply patch

88. git reset --soft HEAD~1 – Soft reset

89. git archive --format=tar.gz HEAD > archive.tar.gz
– Archive repo

90. git grep "search_term" – Search for text

91. git bisect start – Start binary search

92. git ls-files – List tracked files

93. git update-index --assume-unchanged file – Ignore
file temporarily

94. git push origin --delete branch_name – Delete
remote branch

95. git pull --all – Fetch all branches

96. git submodule add URL path – Add a submodule

97. git submodule update --init --recursive – Update
submodules

98. git commit --amend -m "Updated commit message" –
Amend commit

99. git fetch --prune – Remove deleted remote
branches

100. git push --mirror destination_url – Mirror
repository

101. git worktree add ../branch_name branch_name –
Work with multiple branches
    

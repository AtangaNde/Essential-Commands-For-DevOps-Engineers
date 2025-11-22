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

51. git init – Initialize a git repository

52. git clone repo_url – Clone a repository

53. git status – Show changes

54. git add . – Stage all changes

55. git commit -m "msg" – Commit changes

56. git push origin branch – Push changes

57. git pull origin branch – Pull latest changes

58. git checkout branch – Switch branch

59. git branch -a – List all branches

60. git merge branch – Merge branch into current
branch

61. git log --oneline – Show commit history

62. git diff – Show changes

63. git stash – Stash changes

64. git stash pop – Apply stashed changes

65. git reset --hard HEAD~1 – Reset last commit

66. git revert commit_id – Revert commit

67. git tag -a v1.0 -m "Version 1.0" – Create tag

68. git push --tags – Push tags

69. git rm file – Remove a file from git

70. git clean -fd – Remove untracked files

71. git config --global user.name "Your Name" – Set
global username

72. git config --global user.email "you@example.com"
– Set global email

73. git show commit_id – Show commit details

74. git blame file.txt – Show changes by line

75. git remote -v – Show remote repositories

76. git remote add origin URL – Add remote repo

77. git rebase branch – Rebase branch

78. git cherry-pick commit_id – Pick specific commit

79. git fetch – Fetch remote changes

80. git log --graph – Show graphical commit log

81. git branch -d branch_name – Delete branch

82. git pull --rebase – Rebase while pulling

83. git push --force – Force push changes

84. git reflog – Show reflog

85. git diff HEAD~1 – Show last commit changes

86. git apply patch.diff – Apply patch

87. git reset --soft HEAD~1 – Soft reset

88. git archive --format=tar.gz HEAD > archive.tar.gz
– Archive repo

89. git grep "search_term" – Search for text

90. git bisect start – Start binary search

91. git ls-files – List tracked files

92. git update-index --assume-unchanged file – Ignore
file temporarily

93. git push origin --delete branch_name – Delete
remote branch

94. git pull --all – Fetch all branches

95. git submodule add URL path – Add a submodule

96. git submodule update --init --recursive – Update
submodules

97. git commit --amend -m "Updated commit message" –
Amend commit

98. git fetch --prune – Remove deleted remote
branches

99. git push --mirror destination_url – Mirror
repository

100. git worktree add ../branch_name branch_name –
Work with multiple branches
    

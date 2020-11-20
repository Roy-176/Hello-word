# Git common command
## git basic syntax
| syntax  | describe |
| ------- | ------------ |
| git init | 將此目錄增加git功能 |
| git add -A | 將所有檔案加入到追蹤，並且在集結狀態 |
| git commit -m "msg" | 紀錄修改的資訊，並將檔案儲存至站存區 |

![](https://github.com/Roy-176/git/blob/main/img/git.png)

## git add
| syntax  | describe |
| ------- | ------------ |
| git add <file> | 將指定檔案加入集結狀態 |
| git add -A | 將所有檔案加入到追蹤，並且在集結狀態 |
| git add --all | 同上 |

## git commit
| syntax  | describe |
| ------- | ------------ |
| git commit | 紀錄修改的資訊，並使用vim作為輸入訊息的工具 |
| git commit -m "msg" | 紀錄修改的資訊，並將檔案儲存至站存區 |

## git remote
| syntax  | describe |
| ------- | ------------ |
| git remote -v | 查看目前有些遠端目標 |
| git remote rm <remote alias> | 刪除指定別名為"remote alias"的遠端目標 |
| git remote add <remote alias><remote rul> | 增加remote url遠端目標，並且設定別名為remote alias |

## git push
| syntax  | describe |
| ------- | ------------ |
| git push -u <remotes><branch> | 第一次上傳，設定上傳分支，並且推送到指定的遠端伺服器 |
| git push --set-upstream <remote><branch> | 同上 |
| git push | 非第一次上傳，推送到預設的遠端伺服器及分支 |

## git branch
| syntax  | describe |
| ------- | ------------ |
| git branch | 顯示目前git專案所有的分支和目前所在位置的分支 |

![](https://github.com/Roy-176/git/blob/main/img/gitbranch.png)

![](https://github.com/Roy-176/git/blob/main/img/gitbranch2.png)

## git checkout
| syntax  | describe |
| ------- | ------------ |
| git checkout <branch> | 切換到指定的branch |
| git checkout -b <branch> | 切換到指定的branch，沒有的話就建立 |
| git checkout --<file> | 將檔案回復到上次commit的狀態 |

## git reset
| syntax  | describe |
| ------- | ------------ |
| git reset HEAD <file> | 切換到指定的檔案移出暫存區，變成尚未追蹤的狀態，保存修改 |
| git reset --soft <commit> | 將 HEAD 指標指到指定的 commit，修改會保留 |
| git reset --hard <commit> | 將檔案回復到指定的 commit，並且刪除指定 commit 後的修改 |

## git log
| syntax  | describe |
| ------- | ------------ |
| git log | 顯示過去commit的紀錄 |
| git log <-number> | 顯示過去commit紀錄裡的第N筆 |
| git log --pretty=online | 顯示過去每筆commit的歷史紀錄於一行內 |

## git config
| syntax  | describe |
| ------- | ------------ |
| git config < --system/ --global/ --local> user.name"valeu" | 於指定的層級，設定user.name為value |
| git config < --system/ --global/ --local> alias.="command" | 設定command指令的別名為name |



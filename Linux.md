# <center> Linux  </center>
## vim
> 三种模式：**命令模式（Command mode）**,插入模式（Insert mode），底线命令模式（Last line mode）
- 命令模式：
  + `i`    切换到插入模式，以输入字符
  + `x`    删除当前光标所处的字符
  + `:`	   切换到底线命令模式，在底部输入命令
  + `[ctrl] + [u]`    向上翻半页
  + `[ctrl] + [d]`    向下翻半页
  + `/[word]`         向下搜索参数中的字符 
  + `？[word]`        向上搜索参数中的字符
  + `n`      	      重复上一步搜寻动作 
  + `N` 	      反向进行前一个搜寻动作
  + `yy`	      复制当前行
  + `[n]yy` 	      向下复制n行
  + `y1G`             复制第一行到光标所在行
  + `yG`              复制最后一行到光标所在行
  + `p/P`	      [paste]粘贴在光标 下/上一行
  + `j`               将光标所在行与下一行数据结合成一行
  + `:[line1],[line2]s/word1/word2/g`    将line1-line2 行之间的word1替换为word2
  + `[n]dd`    	      向下删除n行
  + `d1G`             删除光标所在行到第一行数据
  + `dG`	      删除光标所在行到最后一行 
  + `u`		      复原上一个动作(相当于command + z)
  + `[contral]+r`     (相当于 comamnd + shift + z)
- 输入模式：
  + `esc`  退出输入模式
- 底线输入模式：
  + `q`    退出程序
  + `w`    保存文件
## 文件操作
### 操作命令 
- 常用参数：
  + `-a`    所有属性
  + `-f`    强制（force）
  + `-i`    交互模式（在进行操作前会询问）
  + `-r`    递归
  + `-l`    列表
- `mkdir`  创建文件夹
- `cd`     进入某个目录
- `ls`     列出当前目录的文件
- `touch`  创建文件
- `cp`	   复制文件（或目录）
- `mv`     移动或重命名
  + `mv [oldName] [newName]`  第二个参数如果有此文件，移动到此文件中，如果没有则会重命名
  + `mv /oldName/newPath/NewName`  移动并重命名
- `rm`	   删除文件或目录
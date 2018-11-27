git是一个软件，是一个开源的分布式版本控制系统，能够帮助使用者查看及管理自己所完成的程序及文件。而Github是一个网站，是一个全球范围内的开源网站，在上面我们能够学习到很多东西，能够查看别人的文件，并能够交流等。
git 使用流程：
1.创建一个空文件夹，右键点击该文件夹并选择“Git Bash Here”,输入 git clone 然后右键选择paste粘贴Github上库的地址，再按回车键执行 2.然后当本地文件发生改变时，右键点击与你库的名字相同的那个文件夹，选择“Git GUI Here”,再单击Unstaged Changes 下出现的文件夹，该文件夹就会跳到Staged Changes ， 然后点击Commit Changes，输入你所更改的情况，点击Commit ，再点push，到出现success就成功了 3当Github上的库发生变化时，同步到本地，右键点击与你本地的库名字相同的那个文件夹，选择“Git GUI Here”,选择Remote>>Fetch from>>origin, 出现success后点击close，再点击Merge>>Local Merge>>Merge，success后关闭即可

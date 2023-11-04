# 作业1：Git 练习 - 日记系统（20’）

本次练习的目标是通过一个简单的日记应用项目，帮助掌握和加深对git的使用技巧。请仔细阅读以下步骤，并完成每一个任务。

## 项目说明
假设你正在管理一个线上日记系统。在这个仓库中包含多个分支，用户可以创建、编辑日记，上传图片，并查看之前的日记。你们的团队使用Git进行版本控制，并希望通过以下任务来进一步熟悉Git的使用。请首先fork课程提供的日记系统仓库然后开始git命令的练习。

## 任务一（20'）
你想要创建名为feature-newFunc的新分支。然后你在新分支上进行了两次提交，你希望合并这个分支上的两次提交并合并整个功能到main分支。  
**操作指示：**
1. 创建新的分支:（5‘）
* 创建一个名为feature-newFunc的新分支，并切换到这个分支。
2. 在feature-newFunc分支上进行两次提交。（2‘）
* 操作内容如下：  
  1) 第一次提交在diary.txt文件中（mydiary文件夹下），添加以下条目：2023-10-28: Started developing a new feature.  
     * 保存文件。
     * 提交这个更改，并在提交信息中描述为："Added diary entry for feature work".  
  2) 第二次提交再次在diary.txt文件中，添加以下条目：2023-10-29: Continued work on the new feature.  
     * 保存文件。
     * 提交这个更改，并在提交信息中描述为："Added another diary entry for feature work".
3. 合并feature-newFunc分支上的两次提交，并合并整个功能到main分支。（13‘）

## 任务二（20'）
你正在experiment分支上进行实验性工作。experiment分支上已经进行了两次commit操作（修改test文件夹下node.txt），中途你决定将第一次commit操作（comment为：Added new approach details.）的更改应用到main分支，但不希望更改提交历史。请完成这个操作。  
**操作指示：**
1. 确保你处于最新的main分支上（2’）  
2. 从experiment分支上获取所需更改（5’）  
3. 应用选中的提交（请选择第一次commit（comment为：Added new approach details.））到main分支（10’）  
4. 上传更改到远程仓库（3’）

## 任务三（20'）
dev分支上进行了4次提交（修改backend文件夹下project.txt），但是发现第三次（comment为：Some content was added repeatedly ））和第四次提交（comment为：Mistakenly added irrelevant content））是错误的于是想回退到上一次提交（comment为：Add new content）），但同时想保留这些错误提交的记录。  
**操作指示：**
1. 确保在正确的分支上进行操作（2’） 
2. 检查当前的提交历史（3’） 
3. 回退到目标提交（5’） 
4. 再次提交（5’） 
5. 确认更改
6. 推送到远程仓库（5’） 

## 任务四（20'）
在main分支上已经有了一个前端网页的基本版本（在frontend文件夹下）。而在feature-upload分支上，你正在开发一个允许用户上传图片的新功能。任务是查看两个分支之间的差异并决定是否要合并它们。如果有合并冲突，请解决冲突后合并。  
**操作指示：**
1. 在main分支上提交修改:（5’）
* 操作内容如下：  
  * 切换到main分支，在styles.css文件中修改body的字体（第一行）为：body { font-family: 'Times New Roman';  }
  * 提交这个修改。  
2. 切换到feature-upload分支。（5’）  
3. 查看feature-upload与main分支之间的差异。（5’）  
4. 决定是否合并feature-upload分支到main。如果有合并冲突，请解决冲突后合并。（5’）

## 任务五（20'）
已经创建了一个名为documentation的新分支，以便更新项目的文档。
在documentation分支上，已经进行了以下操作：  
* 		添加了一个新的INSTALL_GUIDE.md文件，描述了如何安装该项目。
* 		更新了PROJECT_OVERVIEW.md，增加了一些关于项目的新功能的描述。
* 		添加了一个CONTRIBUTING_GUIDE.md文件，为其他开发者提供了如何为该项目贡献代码的指南。
* 		修复了PROJECT_OVERVIEW.md中的一个小错误。
但在提交之后，你意识到可能更有意义地组织这些提交。特别是，你想：
* 将PROJECT_OVERVIEW.md的两次更改合并为一个提交。
* 将INSTALL_GUIDE.md和CONTRIBUTING_GUIDE.md的更改交换位置，使得安装指南在贡献指南之后。
你的任务是，正确地重组这些提交，然后将更改合并回main分支。  
**操作指示：**
1. 切换到documentation分支（3’）
2. 开始交互式重组（5’）
3. 重新排列、合并提交（5’）
4. 完成重组后，将更改合并回main分支（4’）
5. 将更改push回远程仓库（3’）

## 提交作业：
请将你们的操作指令记录下来放在git comment.txt中，并上传到main分支的根目录下。  
完成所有任务后，请提交你的仓库链接。

## 注意事项：
每次操作请确保你在正确的分支上进行。  
操作指示为大家提供了一个可行的解决任务的步骤，但是你也可能有其他办法达到目的，我们只检查最终结果是否正确。  
使用git log命令可以帮助你查看你的提交历史，从而确定你的操作是否正确。  
祝你在本次作业中学到更多关于Git的知识！



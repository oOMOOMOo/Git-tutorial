# Git-tutorial
## GitHub workflow
一般情况
### Issue -> branch -> pull requests -> code review 
### Issue
一般我们使用github issues来跟踪待办事项和进展. 
如何建立Issue?
可以通过在提交信息或描述中引用**Issue编号**,将git提交附加到问题上.
Issue编号可以在Issue标题和URL中找到.
(在信息中加入 fixes #issue number,或 close #issue number 可以自动关闭issue)
### Branch
建立 branch **git branch NAME_OF_THE_NEW_BRANCH**(工作中一般会加Issue number,方便查找)  
问题解决后 使用 git push 将该branch推送回gitHub 仓库.
### Code review
所有代码都应该接受Code review. 这可以确保代码质量和一致性. 这也可以让团队其他成员了解项目中发生的事情.
### pull requests
每当创建一个pull request的时候. 最好团队其他成员之一对此进行代码审查. 审查结束后由问题所有者通过额外的commit来解决该分支的审查意见.
当所有审查人员对代码满意后,则可以approve,从而结束审核.然后将此branch合并到主branch(通常是master)  
### [go tutorial](https://github.com/oOMOOMOo/Git-tutorial/wiki/Tutorial)

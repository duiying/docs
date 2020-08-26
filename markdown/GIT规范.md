# GIT规范

### commit规范

基本格式：type: subject  

type 用于说明 commit 的类别，只允许使用下面 7 个标识。  

- feat：新功能（feature）
- fix：修补 bug
- docs：文档（documentation）
- style： 格式（不影响代码运行的变动）
- refactor：重构（即不是新增功能，也不是修改 bug 的代码变动）
- test：增加测试
- chore：构建过程或辅助工具的变动  

subject 是 commit 目的的简短描述，不超过 50 个字符。  

- 以动词开头，使用第一人称现在时，比如 change，而不是 changed 或 changes
- 第一个字母小写
- 结尾不加句号（.）

### 分支规范

常用分支：  

- master 分支，主分支
- develop 分支，开发分支，命名格式：develop-你的名字，如：develop-wangyaxian
- feature 分支，功能分支，命名格式：feature-*
- hotfix 分支，紧急修复分支，命名格式：hotfix-*

# 命令行工具
## 命令
- gsub 提交
- gvsn 升级版本（待实现）

## 材料
- inquirer

## 需求
### 一期需求
实现 gsub 提交

- [x] 顺序 git 的 add commit push
- [x] commit 可选提交类型 (feat fix refactor 等) 和提交文字 
- [x] push 可选是否提交 默认否

### 二期需求
实现 gvsn 升级版本

- [x] 升级版本号，X.Y.Z 可指定三级中的一级（X.Y.Z 分别表示重大更新.增删功能.修复 Bug）
- [x] 生成 git 提交记录，以 chore 的形式并提交到远程仓库（可选）
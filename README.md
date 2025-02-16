# Bear Rlease

[Bear](https://github.com/rizsotto/Bear) 是一个编译数据库生成工具。它可以在构建过程中生成符合 [clang JSON compilation database](http://clang.llvm.org/docs/JSONCompilationDatabase.html) 格式的编译命令数据库，这些信息可用于：

- 代码分析工具
- 重新执行编译
- 其他需要编译命令信息的工具

## 使用说明

基本用法：

```bash
# 执行后会在当前目录生成 compile_commands.json 文件。
bash bear -- <your-build-command>
```

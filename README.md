# dotfile
my own dotfiles

# Linux
 参考学长的，用的pathogen管理插件，其实我一直用的vundle，学长的更简洁些.

 如果要用zsh，首先安装oh-my-zsh.

 [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

```
 $ sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)" 
```
Then, clone this repo(and then remove .vscode) and make.

# Windows
vscode for debug and run code. 

sublime text仅当编辑器用了，每次编译运行还得切出去单独输命令(原始的ctr shift b无法读标准输入)，而且调试只能gdb或打输出，用vscode配置一下，各种姿势，任君选择.

下载vscode的c/c++插件后，json文件在当前目录的.vscode文件修改即可.

[reference](https://code.visualstudio.com/docs/languages/cpp)

（可选）code-runner插件

code-runner的配置在用户设置里自行修改.

[vscode-code-runner](https://github.com/formulahendry/vscode-code-runner)

## 需要配置的插件参考
> ~/.zshrc
安装参考：https://blog.csdn.net/successli1994/article/details/81746806
```xml
plugins=(
  git
  github
  autojump
  zsh-syntax-highlighting
  zsh-autosuggestions
)

```

## .zshrc文件参考
```sh
....
# Example aliases
# alias zshconfig="mate ~/.zshrc"
# alias ohmyzsh="mate ~/.oh-my-zsh"
. /usr/share/autojump/autojump.zsh
source /home/loulvlin/.oh-my-zsh/custom/plugins/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
source /home/loulvlin/.oh-my-zsh/custom/plugins/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
source /home/loulvlin/.oh-my-zsh/custom/plugins/incr/incr*.zsh

MAVEN_HOME=/home/loulvlin/soft/apache-maven-3.6.3
export PATH=$PATH:$MAVEN_HOME/bin


export GRADLE_HOME=/home/loulvlin/soft/gradle-6.3
export GRADLE_USER_HOME=/home/loulvlin/soft/gradlerepo/.gradle 
export PATH=$PATH:$GRADLE_HOME/bin



```

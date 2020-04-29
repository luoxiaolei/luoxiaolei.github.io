---
layout: post
title: MacOS install Python and pyenv
categories: [Install]
excerpt: 
---

### 安装
1. 安装Python
```
brew install python
```

2. 安装pyenv
```
git clone https://github.com/pyenv/pyenv.git ~/.pyenv

配置zsh
echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.zshrc
echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.zshrc
echo 'eval "$(pyenv init -)"'' >> ~/.zshenv
echo 'eval "$(pyenv virtualenv-init -)"'' >> ~/.zshrc
```

### pyenv常用命令
1. 查看所有Python版本
```
pyenv versions
```

2. 查看当前使用的Python版本
```
pyenv version
```

3. 切换Python版本
```
pyenv global versionCode
```

4. 安装指定版本Python
```
pyenv install versionCode
```

5. 卸载指定版本Python
```
pyenv uninstall versionCode
```

### 常见问题
1. 使用pyenv时，出现pyenv global xxx无法成功切换版本的问题,执行如下命令即可
```
pyenv local --unset
```

### 参考链接
- [pyenv切换版本失败](https://blog.csdn.net/Tramac/article/details/78790035)
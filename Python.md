# Python CheatSheet

## brew install, update
[Brew.md](https://github.com/liante0904/CheetSheetRepo/blob/master/Brew.md)

## pre-install package(for python)
`$ xcode-select --install`   
`$ brew install readline xz`

## pyenv, pyenv-virtualenv install
`$ brew install pyenv`  
`$ brew install pyenv-virtualenv`

## add .bash_profile 

`$ vi .bash_profile`

 **copy & paste below code**

~~~
export PATH="$HOME/.pyenv/bin:$PATH"
eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"
~~~

## python install (in pyenv)
`$ pyenv install --list`  
`$ pyenv install 3.5.2`


## check version
### system python ver  
`$ python --version`  
### pyenv python ver
 `$ pyenv versions`

## change Python Ver 
`$ pyenv global 3.5.2`
`$ pyenv versions`


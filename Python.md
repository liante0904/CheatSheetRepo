# Python CheetSheetRepo

## brew install
   ``$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"``

  ``$ brew update``

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


### Dependency Management
## First time only
1. Install brew
``` bash
brew install pyenv
```
2. The following should create a snippet to be added to .profile
```bash
curl https://pyenv.run | bash
```

if not, add the following snippet to your .profile file such as `.bash_profile`, `.zshrc`
```bash
export PATH="~/.pyenv/bin:$PATH"
eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"
```
3. To install a python version 3.8.8 with pyenv
``` bash
pyenv install 3.8.8
```
4. To set your python version globally
``` bash
pyenv global 3.8.8
```
5. To check pyenv versions available
``` bash
pyenv versions
```
6. Install poetry with pip so you can take advantage of pyenv
``` bash
pip install poetry
```

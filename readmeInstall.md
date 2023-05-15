
1. brew update.不更新会导致pyenv的版本中午Python更高版本
	brew update
	brew install cmake protobuf rust python@3.10 git wget


2. download python 3.10.6
	brew install pyenv
	pyenv install python@3.10.6
	pyenv global
	pyenv --help

3. brew install cmake protobuf rust python@3.10 git wget

4. pip3 install gfpgan
   pip install ftfy regex tqdm
   pip install git+https://github.com/openai/CLIP.git

5. pip config set global.trusted-host pypi.tuna.tsinghua.edu.cn && pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple/

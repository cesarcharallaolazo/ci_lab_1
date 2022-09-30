# Steps MacOs

0. pip install virtualenv
1. pyenv install 3.8.3
2. virtualenv venv --python=python3.8
3. source venv/bin/activate
4. pip freeze -> no hay nada
5. touch requirements.txt
6. pip install -r requirements.txt

# Steps Linux - Ubuntu 20.04.4 LTS (Focal Fossa)
0. init installations
- sudo apt-get update
- sudo apt install python3-pip
- sudo apt install python3-virtualenv
- sudo apt install python3-venv
1. conda create -n "ci_lab" python=3.8.3
2. conda activate ci_lab
4. pip freeze -> nothing !
5. touch requirements.txt
6. pip install -r requirements.txt
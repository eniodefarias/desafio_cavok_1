# desafio_cavok_1
desafio_cavok


## briefing
 - isso
 - aquilo
 - aquele lá

## linguagens e frameworks
 - python
 - django
 - xyz








---

# comandos úteis

## GIT
 - lembre se trocar o nome do **branch** de acordo com a necessidade



### iniciar o repo
    git init
    git remote add origin https://github.com/eniodefarias/desafio_cavok_1.git



### puxar "git pull" da branch "ajuste_01"
    git pull -f origin ajuste_01


#### ou da main, se necessário:
    git pull -f origin main




### trocar branch main
    git branch main ; git checkout main 


#### ou trocar branch para uma de teste, se for fazer algum ajuste
    git branch ajuste_01 ; git checkout ajuste_01

### gerar o venv

#### no windows, no cmd do DOS:
    C:\Users\user\AppData\Local\Programs\Python\Python39\python.exe -m venv .venv

#### no windows, no gitbash:
    /c/Users/user/AppData/Local/Programs/Python/Python39/python.exe -m venv .venv

#### no linux, no shell
    /home/user/.pyenv/shims/python3 -m venv .venv


### enviar "git push" da branch
    git add . ; git add * ; git commit -m "fix: ajuste de log debug com prints" ; git push -f origin ajuste_01

## atualizar python
    .venv/Scripts/python.exe -m pip install PyInstaller
    .venv/Scripts/python.exe -m pip install --upgrade pip


### instalar os requirements.txt na mão
#### usando o gitbash
     cat requirements.txt|sort|uniq | xargs -n 1 .venv/Scripts/pip3.exe install; .venv/Scripts/pip3.exe --upgrade pip ; .venv/Scripts/python.exe -m pip install --upgrade pip

#### usando o shell do linux
    cat requirements.txt|sort|uniq | xargs -n 1 .venv/bin/pip install; .venv/bin/pip --upgrade pip ; .venv/bin/python3 -m pip install --upgrade pip


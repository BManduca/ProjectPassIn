## Diário de aprendizado

- ### Neste espaço será armazenado todas as explicações, termos e novidades expostas dentro do projeto.

- ### Material complementar:
    - https://efficient-sloth-d85.notion.site/Python-17d72ad083874c57b01a4d9d76f92a25
    - **repo rocket**: https://github.com/rocketseat-education/nlw-unite-python/tree/main

___________________________________________________________________________________________________ 

<br />
<br />

## Instalação de aplicações/ferramentas dentro do projeto

### DBeaver
- **instalação**:
    - Adicione o repositório do programa: 
        - echo "deb https://dbeaver.io/debs/dbeaver-ce /" | sudo tee /etc/apt/sources.list.d/dbeaver.list
        - wget -O - https://dbeaver.io/debs/dbeaver.gpg.key | sudo apt-key add -
    - Atualizar gerenciador de pacotes:
        - sudo apt-get update
    - Instalando programa:
        - sudo apt-get install dbeaver-ce

<br />

### Virtualenv
- **instalação**: pip3 install virtualenv
- **Create and Use Virtual Environments**
    - python3 -m venv .venv
- **Activate a virtual environment**
    - source .venv/bin/activate

<br />

### SQLAlchemy
- **instalação**: pip3 install SQLAlchemy
- **doc**: https://www.sqlalchemy.org/docs/

<br />

### Pytest
- **instalação**: pip3 install pytest
- **doc**: https://docs.pytest.org/en/stable/.

<br />

### Pylint
- Pylint é um analisador de código estático para python 2 ou 3.
- **instalação**: pip3 install pylint

<br />

### Pre-commit
- Um framework para gerenciar e manter pre-commits multilíngues
- instalação: pip3 install pre-commit -> pre-commit install

<br />

### Flask
- Framework de aplicação Web, que foi projetado com intuito de escalar aplicações web complexas, de uma maneira inicial rápida e fácil.
- instalação: pip3 install -U Flask

<br />

### Criando um arquivo geral de configuração Pylint
- pylint --generate-rcfile > .pylintrc

<br />

### Requirements
- Arquivo para registrar as dependências e quais são suas versões
- .venv/bin/pip3 freeze > requirements.txt    

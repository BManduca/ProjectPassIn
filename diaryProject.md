## Diário de aprendizado

- ### Neste espaço será armazenado todas as explicações, termos e novidades expostas dentro do projeto.

___________________________________________________________________________________________________ 

<br />
<br />

## Instalação de aplicações/ferramentas dentro do projeto

### DBeaver
- instalação:
    - Adicione o repositório do programa: 
        - echo "deb https://dbeaver.io/debs/dbeaver-ce /" | sudo tee /etc/apt/sources.list.d/dbeaver.list
        - wget -O - https://dbeaver.io/debs/dbeaver.gpg.key | sudo apt-key add -
    - Atualizar gerenciador de pacotes:
        - sudo apt-get update
    - Instalando programa:
        - sudo apt-get install dbeaver-ce
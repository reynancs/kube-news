## :dart: Objetivo
Praticar o uso de Kubernets em uma máquina local com o k3d, afim de, praticar em uma aplicação web com um banco de dados PostGre.


## :pushpin: Descrição
Para está prática foi utilizado a criação de uma imagem Docker com uma aplicação em node.js e posteriormente gerado o Deployment da aplicação com a criação de um manifesto em formato .YAML.


## :computer: Como rodar a aplicação
1. Realize o fork do projeto e em seguida no seu terminal git bash dê o comando `git clone` para copiar o repositório para sua máquina local.
2. `docker-compose up -d` -> dar este comando no seu terminal do linux ou WSL2 no diretória da aplicação;
3. Criar imagem da aplicação Dockerfile
4. Criar manifesto deployment.yaml para realizar o deployment da aplicação



## :triangular_flag_on_post: Pré-Requisitos
- VS Code v1.72.2
- WSL2 para Windows
- [Docker Desktop](https://docs.docker.com/desktop/install/windows-install/)
- Chocolatey v1.2.0
- k3d v5.4.6
- Kubectl v4.5.7


## :link: Links/Referência


### :bookmark: Notas
A aplicação é exposta usando a porta 8080

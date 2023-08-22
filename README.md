>Tutorial Git
>
>Este tutorial tem por objetivo disponibilizar alguns comandos git de uso frequente, visando a acessibilidade destas informações, por iniciantes na área de versionamento de código.



# Fundamentos do Git e GitHub 

## O que é o Git? 🔗 [Git Docs](https://git-scm.com/doc)

O Git é um sistema de controle de versões distribuído que permite rastrear e gerenciar as alterações em seu código ao longo do tempo. Ele é fundamental para colaboração e desenvolvimento de software.

## O que é o GitHub? 🔗 [Github Docs](https://docs.github.com/pt/get-started)
O GitHub é uma plataforma de hospedagem de código que utiliza o Git como base. Ele oferece recursos de colaboração, rastreamento de problemas, integração contínua e muito mais.

## Configurando o Ambiente
### Instalando o Git

Antes de começar, é necessário ter o Git instalado em seu sistema. Vamos mostrar como fazer isso passo a passo.

### Comando:

```javascript
//Exemplo de instalação do Git em um sistema Linux
sudo apt-get update
sudo apt-get install git
```

# Principais Conceitos do Git
## Commits e Histórico
Aprenda sobre commits, como eles capturam instantâneos do seu código e criam um histórico de alterações.

## Branches
Descubra como as branches permitem que você trabalhe em diferentes partes do código simultaneamente e como mesclá-las para unificar alterações.

# Trabalhando com o Git na Prática
## Criando um Repositório
Siga os passos para criar um novo repositório Git tanto localmente quanto no GitHub.

**Tabela de Referência Rápida: Criar um Repositório**

| Ação | Comando  |  Descrição do comando |        Próximos Passos           |
|:-----|:---------|:----------|:----------------|
|Criar pasta para o projeto|`mkdir MeuProjeto`|Cria nova pasta|Acesse a pasta do projeto|
|Acessar a pasta do projeto|`cd MeuProjeto`|Entra na pasta do seu projeto|Inicialize um repositório Git na pasta|
|Inicializar repositório Git|`git init`|Inicializa um repositório Git na pasta|Inicializa um repositório Git na pasta|
|Adicionar arquivos ao índice|`git add .`|Adiciona arquivos do projeto ao índice|Realize o commit das alterações|
|Realizar um commit|`git commit -m "Primeiro commit"`|Cria um commit com uma mensagem descritiva|Conectar repositório local ao GitHub (se necessário)|
|Conectar repositório local ao GitHub|`git remote add origin <URL do seu repositório>`|Adiciona um repositório remoto (GitHub) como origem|Defina a branch principal|
|Definir branch principal|`git branch -M main`|Define a branch principal do repositório|Enviar alterações para o repositório remoto|
|Enviar alterações para repositório|`git push -u origin main`|Envia as alterações do repositório local para o repositório remoto no GitHub|Continue desenvolvendo o projeto|

## Clonando um Repositório

Aprenda como clonar um repositório existente do GitHub para sua máquina local.

**Tabela de Referência Rápida: Clonar um Repositório**

| Ação | Comando  |  Descrição do comando |        Próximos Passos           |
|:-----|:---------|:----------|:----------------|
|Clonar um repositório|`git clone <URL do repositório>`|Copiar um repositório remoto para o seu PC|Acesse a pasta do repositório clonado|

```bash
# Exemplo de clonagem de um repositório remoto
git clone https://github.com/seu-usuario/seu-repositorio.git
```

## Fazendo Fork de um Repositório
Saiba como fazer um fork de um repositório para sua conta no GitHub.

**Tabela de Referência Rápida: Fazer Fork de um Repositório**

| Ação | Comando  |  Descrição do comando |        Próximos Passos           |
|:-----|:---------|:----------|:----------------|
|Fazer fork de um repositótio|(Feito na interface do GitHub)|Criar uma cópia pessoal de um repositório|Clonar o repositório forkado para o seu PC|

* Realizado na interface do GitHub.

## Criando e Gerenciando Branches
Aprofunde-se nas branches e descubra como criar, trocar, mesclar e resolver conflitos.

**Tabela de Referência Rápida: Criar e Trabalhar com Branches**

| Ação | Comando  |  Descrição do comando |        Próximos Passos           |
|:-----|:---------|:----------|:----------------|
|Criar uma nova branch|`git branch <nome da branch>`|Criar uma nova ramificação no código|Trocar para a nova branch|
|Trocar para outra branch|`git checkout <nome da branch`>|Alternar para uma branch específica|Realizar as alterações desejadas na branch|
|Criar e trocar de branch|`git checkout -b <nome da branch>`|Criar e alternar para uma nova branch|Realizar as alterações desejadas na branch|
|Mesclar branches|`git merge <nome da outra branch>`|Combinar alterações de uma branch com outra|Resolver conflitos, se necessário|

```bash
# Exemplo de criação e troca de branch
git branch minha-branch
git checkout minha-branch

# Exemplo de criação e troca de branch em um único comando
git checkout -b minha-outra-branch

# Exemplo de mesclagem de branches
git checkout main
git merge minha-branch

```
# Próximos Passos
## Trabalho Colaborativo
Explore como colaborar com outros desenvolvedores usando Pull Requests e revisões de código.

## Fluxos de Trabalho Avançados
Conheça fluxos de trabalho avançados, como o Git Flow, para projetos mais complexos.

## Explorando Mais Recursos
Descubra recursos adicionais, como tags, issues, e como usar o Git e GitHub em diferentes tipos de projetos.

Com estes exemplos, você terá um guia completo para entender e começar a trabalhar com o Git e o GitHub. Lembre-se de praticar e explorar continuamente para aprimorar suas habilidades.


## Autores
**Aldomar Assolin**
- [@AldomarAssolin](https://github.com/AldomarAssolin)

3° semestre - Análise e Desenvolvimento de Sistemas


### 🔗 Meus Links
[![github](https://img.shields.io/badge/github-000?style=for-the-badge&logo=github&logoColor=white)](
https://github.com/AldomarAssolin)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aldomarassolin)
[![instagram](https://img.shields.io/badge/instagram-B7106B?style=for-the-badge&logo=instagram&logoColor=pink)](https://www.instagram.com/aldomarassolin/)

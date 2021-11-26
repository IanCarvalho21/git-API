<h1 align="center">

 📖 Manual de instruções 📖

</h1>

## Índice

* [Clonagem do repositório](#Clonagem-do-repositório)
* [Criação do ambiente virtual](#Criação-do-ambiente-virtual)
* [Backlog do produto](#Backlog-do-produto)
* [Sitema em desenvolvimento](#Sitema-em-desenvolvimento)
* [Entregas](#Entregas)

<h4>

Esse documento tem como objetivo auxiliar qualquer usuário que tenha interesse em acessar a
página descrita no repositório armazenado e disponível em:
"https://github.com/Api2sem2021/Equipe-1".

A página estará disponível para acesso geral entre os dias 28/11/2021 e 25/12/2021 no endereço
"http://20.106.157.191:5000" para acessá-la, basta digitar o endereço em seu navegador de
preferência, o uso de AdBlock pode causar mal funcionamento em algumas páginas (Por ser parte
do projeto integrador a mesma não possui anúncios).

Caso o período de hospedagem já tenha se excedido, seguem as instruções necessárias para fazer
uso da página localmente (os comandos utilizados podem variar entre sistemas operacionais, as
instruções a seguir foram feitas com o usuário do SO Windows em mente) adiantamos que o
primeiro passo é ter em sua máquina a linguagem de programação Python e o pacote Pip.

</h4>


## Clonagem do repositório

<h4>
Para iniciar a página localmente o usuário precisa baixar o arquivo zip do repositório ou
cloná-lo a partir do Prompt de comando de seu computador, nesse documento cobre
apenas o método de download com o intuito de facilitar a experiência do usuário:
</h4>

<h4>
(segue gif de como baixar o repositório)
</h4>

## Criação do ambiente virtual 

<h4>

Criação do ambiente virtual para instalação dos requisitos:
Já com o repositório clonado, o usuário deve encontrar a pasta “Frontend” e copiar o
caminho até ela, no SO Win10, a maneira mais simples é entrando em propriedades e
copiando o local onde a pasta está armazenada, a seguir adicionando “\FrontEnd" (sem
as aspas) em frente ao caminho para especificar a pasta desejada para a criação do
ambiente virtual:

Como demonstrado, o usuário deve acessar seu Prompt de comando (cmd) e digitar o
seguinte comando (RETIRAR ASPAS SIMPLES PARA UTILIZAR OS COMANDOS):

__‘Cd "C:\Users\lobat\Documents\GitHub\Equipe-1\FrontEnd"’__

Checar se o cmd reconheceu o caminho para a pasta Frontend

__‘py -3 -m venv venv’__( criando um ambiente virtual com o nome venv)

Ao criar o ambiente virtual o usuário deve ativá-lo
__‘venv\scripts\activate’__ (tente barras comuns caso não consiga)

E então instalar o arquivo requirements

__‘pip install -r requirements.txt’__

</h4>



* Requistos funcionais
   ---
   - [X] Linguagem Python, HTML e CSS (Requisito Fatec).
   - [X] Clonagem dos githubs disponibilizados no site da Fatec SJC.
   - [X] Raspar do site da Fatec os links de acesso para os vídeos da feira de soluções.
   - [ ] Gerar um código para incorporar na página da Fatec SJC contendo a indexação de todos os projetos.
   - [X] Todas as pastas devem seguir uma organização por curso, semestre, turma e equipe.
   - [X] Site para a exposição dos projetos.




* Requisitos não funcionais
  ---
  - [ ] Manual de instalação.
  - [X] Organização do github.

## User Story

| Quem | O que? | Para |
|:--------------:  | :----------:|:---------------------------------------------------------|
| Desenvolvedor | Gostaria de uma interface visual.  | Para que facilite a execução do código de raspagem e coloque-o no banco de dados. |
| Desenvolvedor | Gostaria de uma forma de clonar os reposotórios de forma automática.  | agilizar o processo de clonagem dos repositórios das próximas turmas que virão.  |
| Desenvolvedor | Gostaria de uma página responsiva e fácil de utilizar.  | Para que facilite o uso do sites para o cliente.  |

## Backlog do produto

Tarefa | Prioridade
:--- | :--- |
Criar página de turmas/semestres | Alta Prioridade
Criar página home | Alta Prioridade
Clonagem dos repositórios | Alta Prioridade
Raspar do site da Fatec os links de acesso para os vídeos da feira de soluções | Prioridade Média
Coleta de links dos vídeos dos projetos anteriores | Prioridade Média
Layout do Github | Prioridade Baixa
Organização por  curso, semestre, turma e equipe dos repositórios | Prioridade Baixa
Protótipo linkado ao site da FATEC | Prioridade Média
Protótipo de raspagem de links automático | Prioridade Média
Redirecionamento para os links no site protótipo | Prioridade Média



## Sitema em desenvolvimento

### Wire Frame da Página Home

<div align="center">
  <img src="https://user-images.githubusercontent.com/90697929/133831169-dca44851-482f-4e1b-b956-b899eb0302f6.gif" width="700px"/>
</div>

### Página Home

<div align="center">
  <img src="https://user-images.githubusercontent.com/90697929/133859310-9c8fb732-d5c9-4185-ba38-b085acc14040.gif" width="700px"/>
</div>

### Wire Frame da Página das Salas
<div align="center">
  <img src="https://user-images.githubusercontent.com/90697929/133831717-1e3ee1b3-8558-4760-a248-aa7bf15845cb.png" width="700px"/>
</div>

### Página Home das Salas 

<div align="center">
  <img src="https://user-images.githubusercontent.com/90697929/133859404-5ad2a5fa-a9a9-4f52-a051-2fa4ad1cabf5.gif" width="700px"/>
</div>

## Entregas

* Sprint 1 (30/08/2021 - 19/09/2021)
   - Clonagem dos githubs.
   - Site para a exposição dos projetos.
   - Organização do github por curso, semestre, turma e equipe.
   - raspagem dos vídeos da feira de soluções.

* Sprint 2 (20/09/2021 - 10/10/2021)
    - Protótipo inicial linkado ao site da Fatec SJC.
    - Protótipo de GUI para a raspagem automática do site da Fatec SJC.
    - Redirecionamento para os repositórios clonados no site protótipo.

* Sprint 3 (18/10/2021 - 07/11/2021) 
    - Implementação do Flask 
    
* Sprint 4 (08/11/2021 - 28/11/2021)
   - Manual de instruções
   - Hospedagem do site na web
  
## Tecnologias Utilizadas  

<div>
  <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg"/>Figma 
  <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg"/> HTML5
  <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg"/> CSS3
  <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg"/> GITHUB
  <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg"/> PYTHON <br>
  <img width="50 rem" src="https://icons-for-free.com/iconfiles/png/512/Flask-1324888719511065447.png"/> FLASK
  <img width="50 rem" src="https://seeklogo.com/images/M/microsoft-azure-logo-85055C44BE-seeklogo.com.png"/> AZURE
  <img width="50 rem" src="https://cdn-icons-png.flaticon.com/512/919/919853.png"/> DOCKER
</div>

<h1 align="center">

 📖 Manual de instruções 📖

</h1>

## Índice

* [Clonagem do repositório](#Clonagem-do-repositório)
* [Criação do ambiente virtual](#Criação-do-ambiente-virtual)
* [Iniciando Flask](#Iniciando-Flask)
* [Referências](#Referências)

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

<h4>
(segue o gif mostrando os comandos)
</h4>

## Iniciando Flask

<h4>
Após cumprir o ultimo passo, basta escrever ‘flask run’ em seu cmd, isso irá iniciar o
flask e hospedar a página de forma local na porta padrão do 5000, basta copiar o endereço
que será impresso com o comando Ctrl+Shift+C (Ctrl+C irá finalizar a hospedagem) e
colar em seu navegador de preferência!
Ao finalizar basta voltar ao cmd e digitar Deactivate ou Ctrl+C
</h4>

<h4>
(segue o gif mostrando os comandos)
</h4>
  
## 📚 Referências 📚

<https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf>
<https://flask-ptbr.readthedocs.io/en/latest/>
<https://www.docker.com/get-started>


<p align=center>
  <img src="https://videosdeti.com.br/wp-content/uploads/2018/12/git-githu-cover.png" width=500/>  
</p>

<h3 align="center">
  <a href="https://git-scm.com/">Git</a> e <a href="https://github.com/">GitHub</a>: Controle e Compartilhe seu Código
</h3>

<h1 align=center>
<img src='https://img.shields.io/badge/Autor-Erick%20Amorim-191F2B?style=flat-square'/>
  <a href="https://www.linkedin.com/in/erick-amorim-265667214/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</h1> <br>
 
<p align="center">
 <a href="#objetivo">Objetivo</a> •
 <a href="#roadmap">Roadmap</a> • 
</p> <br>

<h2 id='objetivo'>Objetivo</h2> 

```
 Listar os principais comandos do Git e explanar algumas utilidades do GitHub.
```

<h2 id='roadmap'>Roadmap</h2>

* [Configurações Iniciais](#config-iniciais)
  * [git config --global user.name](#1)
  * [git config --global user.email](#2)
* [Comandos de Versionamento](#com-vers)
  * [git](#3)
  * [git init](#4)
  * [git status](#5)
  * [git add [nome_do_arquivo]](#6)
  * [git rm --cached [nome_do_arquivo]](#7)
  * [git add .](#8)
  * [git commit -m](#9)
  * [git log](#10)
* [Comandos de Branchs](#com-bran)
  * [git branch](#11)
  * [git branch [nome_da_branch]](#12)
  * [git checkout [nome_da_branch]](#13)
  * [git checkout -b [nome_da_branch]](#14) 
  * [git branch -d [nome_da_branch]](#15)
  * [git merge [nome_da_branch]](#16)
* [Comandos entre Git e GitHub](#com-git-github)
  * [git clone](#17)
  * [git remote add origin 'Caminho do Repositório'](#18)
  * [git remote -v](#19)
  * [git push 'Caminho do Repositório'](#20)
  * [git pull](#21)
* [Comandos de Stash](#com-stash)
  * [git stash](#22)
  * [git stash --include-untracked](#23)
  * [git stash list](#24)
  * [git stash pop](#25)
  * [git stash pop stash@{}](#26)

<h2 id='config-iniciais'>Configurações Iniciais</h2>
<p> Os primeiros comandos gits destinam-se a configuração do email e usuário do git. A fim de identificar o responsável por modificações e  alterações do código.</p>

| Comando     | Descrição                           |
| :---------- | :---------------------------------- |
| <p id='1'>`git config --global user.name 'Nome do Usuário Aqui'`</p> | Identifica o nome do usuário que está utilizando o git. |
| <p id='2'>`git config --global user.email 'Endereço do E-mail Aqui'`</p> | Identifica o e-mail de quem está utilizando o git. |

<h2 id='com-vers'>Comandos de Versionamento</h2>

| Comando     | Descrição                           |
| :---------- | :---------------------------------- |
| <p id='3'>`git`</p> | Exibe comandos disponíveis do git. |
| <p id='4'>`git init`</p> | Inicializa um repositório na pasta atual. |
| <p id='5'>`git status`</p> | Exibe o status do repositório. |
| <p id='6'>`git add nome_do_arquivo`</p> | Adiciona o arquivo ao repositório. Trata-se de um empacotamento, um 'pré-commit'. |
| <p id='7'>`git rm --cached nome_do_arquivo`</p> | Reverte o passo do git add. O arquivo volta a ser untracked. |
| <p id='8'>`git add .`</p> | Adiciona todos os arquivos da pasta ao repositório. |
| <p id='9'>`git commit -m "Texto de Commit Aqui"`</p> | Realiza o commit do repositório atual. |
| <p id='10'>`git log`</p> | Exibe o histórico dos commits. |

<h2 id='com-bran'>Comandos de Branchs</h2>

| Comando     | Descrição                           |
| :---------- | :---------------------------------- |
| <p id='11'>`git branch`</p> | Lista os branchs disponíveis.|
| <p id='12'>`git branch [nome_da_branch]`</p> | Cria uma branch nova. |
| <p id='13'>`git checkout [nome_da_branch]`</p> | Navega entre as branchs. |
| <p id='14'>`git checkout -b [nome_da_branch]`</p> | Cria uma branch e já entra nela. |
| <p id='15'>`git branch -d [nome_da_branch]`</p> | Remove uma branch do repositório. |
| <p id='16'>`git merge [nome_da_branch]`</p> | Atualiza as modificações feitas em uma outra branch para a branch atual.|

<h2 id='com-git-github'>Comandos entre Git e GitHub </h2>

| Comando     | Descrição                           |
| :---------- | :---------------------------------- |
| <p id='17'>`git clone `</p> | Clona um repositório do GitHub na máquina local. |
| <p id='18'>`git remote add origin 'Caminho do Repositório'`</p>| Conecta um repositório remoto com um repositório local|
| <p id='19'>`git remote -v`</p> | Exibe os diretórios remotos. |
| <p id='20'>`git push 'Caminho do Repositório'`</p> | Atualiza o repositório remoto com as modificações do repositório local. |
| <p id='21'>`git pull 'Caminho do Repositório'`</p> | Atualiza o repositório local com as modificações do repositório remoto. |

<h2 id='com-stash'>Comandos de Stash</h2>

| Comando     | Descrição                           |
| :---------- | :---------------------------------- |
| <p id='22'>`git stash `</p> | Reserva alterações antes de serem commitadas. |
| <p id='23'>`git stash --include-untracked`</p>| Reserva alterações antes de serem commitadas de arquivos untrackeds. |
| <p id='24'>`git stash list`</p> | Exibe os stashes. |
| <p id='25'>`git stash pop`</p> | Retorna à última stash. |
| <p id='26'>`git stash pop stash@{número da stash}` | Retorna à stash especificada. |

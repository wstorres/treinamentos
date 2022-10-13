##### LABORATÓRIO<!--Obrigatorio-->
<SUB>[GIT](#) | [GITHUB](#) | [CÓDIGO](#) |</SUB>


<div class="social social-user" align="right" width-full border color-bg-default>

[![Github Badge](https://img.shields.io/badge/-Github-000?style=flat-square&logo=Github&logoColor=white&link=(https://github.com/wstorres))](https://github.com/wstorres) [![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/wstorres/)](https://www.linkedin.com/in/wstorres/)
</div>


<div class="avatar avatar-user width-full border color-bg-default">
<img align="left" width="65" height="65" style="border-radius: 65px" 
border="1" hspace="20" src="https://avatars.githubusercontent.com/u/44095306?v=4">
</div>


<div class="nome nome-user" align="left"> 

**About me**
<sub><strong>Wagner Torres</strong> | 12 Out 2022</sub>
</div>


<br />
<br />


<h2 align="center">GIT - Sistema de Versionamento</h2>
<!--(Obrigatorio)-->

GIT é um Sistema de Controle de Versões de software Distribuído — ou DVCS, para auxiliar o desenvolvedor na criação de software e o trabalho em equipe.

Estes sistemas de controle possuem a função de registrar quaisquer alterações feitas em cima de um código, armazenando essas informações e permitindo que, caso seja necessário, um(a) programador(a) possa regredir a versões anteriores de uma aplicação de modo simples e rápido.

Este tipo de sistema também simplifica muito o processo de compartilhamento de um projeto com um time, por exemplo, ou com outros(as) programadores(as).

Qual a vantagem de usar o Git?

Para programadores(as) que utilizam o GIT, reincluir a funcionalidade é uma tarefa simples: basta buscar, em seu repositório, a versão que a contempla e retomá-la.

Para aqueles(as) que não utilizam, talvez seja necessário reescrever o código desta função, consumindo novamente o tempo gasto para desenvolvê-la da primeira vez.

Outra vantagens de usar o GIT é a economia de tempo e recursos, uma vez que a consulta de diferentes versões de uma mesma aplicação é muito recorrente no trabalho do(a) programador(a).

Outro grande benefício do GIT é justamente o fato de ele ser um sistema distribuído.

Isso significa que, diferentemente de outros sistemas de controle de versionamento populares na época em que foi lançado, o GIT possui repositórios, e não somente um único local com o histórico de seu trabalho.

### **Os conceitos do Git**
Para começar a utilizar o GIT, é importante que você reconheça e compreenda alguns dos principais conceitos utilizados pela ferramenta.

Esta compreensão prévia quebrará alguns obstáculos característico dos primeiros momentos em que manipulamos uma plataforma nova.

Abaixo, listarei e explicarei o que significam algumas nomenclaturas básicas muito comuns na manipulação de códigos-fonte no GIT e no GitHub.

- Repositório
Os repositórios são os ambientes criados para armazenar seus códigos.

Você pode possuir um ou mais repositórios, públicos ou privados, locais ou remotos, e eles podem armazenar não somente os próprios códigos a serem modificados, mas também imagens, áudios, arquivos e outros elementos relacionados ao seu projeto.

É através dos seus repositórios públicos que outros programadores poderão ter acesso aos seus códigos no GitHub, podendo, inclusive, cloná-los para adicionar melhorias.

- Branch
Branch é o nome dado a uma versão (ramificação) do projeto. 

Isso é útil porque possibilita gerenciar múltiplas alterações acontecendo simultaneamente. Por exemplo, podemos fazer com que cada equipe de desenvolvimento

- Merge
Para unir as modificações feitas em um branch ao código original, utilizamos o comando merge.

Com esta funcionalidade, todas as alterações feitas em cópias manipuláveis são inseridas, após aprovadas, no código-fonte original sem complicações.

- Fork
Quando um profissional desenvolvedor precisa começar a trabalhar em um projeto, seu primeiro passo é copiar este repositório para a sua máquina.

Este processo é realizado pelo comando fork.

O fork também é uma funcionalidade útil quando um membro da equipe precisa pegar um código público para manuseá-lo em um editor de código local ou interno.

### **Principais comandos Git**
Se você estiver familiarizado com alguns dos principais comandos do GIT, seus primeiros passos na ferramenta podem se tornar mais descomplicados.

Para isso, trouxemos abaixo uma lista dos comandos mais utilizados pelos programadores(as) e o que eles significam.

- Git Init: este comando dá origem a um repositório novo, local ou remoto, ou reinicializa um repositório já existente;

- Git Clone: este comando clona o código de um repositório para sua manipulação em outro ambiente;

- Git Commit: este comando move os arquivos da state area para um repositório local;

- Git Add: este comando adiciona um arquivo alterado a uma staging area, ou seja, o prepara para ser vinculado a um commit;

- Git Push: este comando envia arquivos de um repositório local para um repositório remoto. No GitHub, por exemplo;

- Gt Pull: ao contrário do push, este comando traz um arquivo do repositório remoto para o repositório local.

- Git Merge: este comando serve para unir arquivos alterados ao arquivo original de um projeto. Em outras palavras, é ele quem une os branchs as commits.

- Git Log: este comando permite a visualização do histórico de commits de um arquivo ou usuário, ou o acesso de uma versão específica.

**Estados de Arquivos**

* Modificado (modified);
* Preparado (staged/index)
* Consolidado (comitted);

	
**Comando específico**

	git help add
	git help commit
	git help <qualquer_comando_git>


**Conclusão - vale a pena utilizar o Git?**

Por ser o mais rápido controle de versionamentos existente hoje no mercado, o GIT vale a pena porque proporciona a seus usuários e estudantes de programação grande otimização de tempo e recursos.

Além do mais, a inclusão do GitHub ao uso desta ferramenta expande significativamente o leque de possibilidades que ela oferece, dando a jovens programadores e programadoras a oportunidade de interagir e observar projetos de profissionais mais experientes na área.
   

------------------------------------------------
### Alguns Procedimentos mais usados
#### 1. Para criar uma pasta

    mkdir nomedapasta

#### 2. Para iniciar o controle de versionamento

    git init 			

#### 3. Para criar um arquivo

    touch nomedoarquivo.md   

#### 4. Clona o endereço do reposito do github para o local:

    git clone https://github.com/nomex/repositorx.git

#### 5. Inicia o controle de versao do repositorio 

    git init
#### 6. Verificar o estados dos arquivos 

    git status

#### 7. Para passar a monitorar um novo arquivo

    git add .

#### 8. Usar o commit depois de já ter feito o git add:  

    git commit -m "argunto do commit'

#### 9. visualizar todos os controles remotos de nosso repositório local

    git remote -v
      

Resultado: 

            origin      git@gitlab.com:delftstack/programmingarticles.git (fetch)
            origin      git@gitlab.com:delftstack/programmingarticles.git (push)
            upstream    git@bitbucket.org:delftstack/test.git (fetch)
            upstream    git@bitbucket.org:delftstack/test.git (push)


#### 10. Upstream da lista de remotos do git

    git remote rm upstream
      

#### 11. Para adicionar o caminho do repositorio remoto

    git remote add origin git@github.com:leocomelli/curso.git

#### 12. Para empurrar os arquivos

    git push -u origin main

------------------------------------------------------------------

### Configurações inicias

As configurações do GIT são armazenadas no arquivo **.gitconfig** localizado dentro do diretório do usuário do Sistema Operacional (Ex.: Windows: C:\Users\Documents and Settings\Leonardo ou *nix /home/leonardo).

As configurações realizadas através dos comandos abaixo serão incluídas no arquivo citado acima.

#### Setup usuário

	git config --global user.name "Wagner Torres"

#### Alterar o user.name 

	git config --global --replace-all user.name "Wagner Torres"	

#### Setup email

	git config --global user.email leonardo@software-ltda.com.br

#### Setup editor

	git config --global core.editor "vim"
	
#### Setup ferramenta de merge

	git config --global merge.tool "vimdiff"

#### Setup arquivos a serem ignorados

	git config --global core.excludesfile ~/.gitignore

#### Listar configurações

	git config --list

--------------------------------------------------------

### Repositório Local

#### Controlar versionamento do repositório

	git init

#### Verificar estado dos arquivos/diretórios

	git status


-----------------------------------------	

### Adicionar arquivos area estage

#### Adicona arquivos espeficico

	git add meu_arquivo.txt

### Adicionar um diretório em específico

	git add meu_diretorio

#### Adicionartodos os arquivos novos e modificados (mas não os deletados).

	git add .

#### Adicona arquivos novos e modificados do diretório atual (Muito semelhante ao comando anterior, mas ignorando os arquivos que começam com .).

	git add *
#### Adicionar todos o seus arquivos ("novos", "modificados" e arquivos "deletados").	

	git add --all
	
#### Adicionar um arquivo que esta listado no .gitignore (geral ou do repositório)

	git add -f arquivo_no_gitignore.txt

#### Exemplificando na tabela 

No Git versão 2.x:

| Comando			| Novos 	| Modificados |	Removidos	| Explicação 							|
| ------------- 	| ----------| ----------- | ----------- |-----------------------------------------------	|
| git add --all		| X			| X			  | X			| Coloca todos arquivos (novos, modificados e removidos) no index/stage |
| git add .			| X			| X			  | X			| Coloca todos arquivos (novos, modificados e removidos) no index/stage¹ |
| git add -u		|  			| X			  |	X			| Faz um update na stagging nos arquivos que já estão sendo rastreados pelo Git.| 
| git add *			|	x		| X			  | x			| Faz o mesmo que o git add . (ignora os arquivos com " . ") |

**Observação**

git add *: vai funcionar exatamente igual ao comando anterior, adicionando somente os arquivos da pasta corrente ao que o comando foi executado.

git add -u, ou git add --update vai fazer um update na stagging nos arquivos que já estão sendo rastreados pelo Git.


---------------------------------------------------------------	
	
## Comitar arquivo/diretório
### Comitar um arquivo

	git commit meu_arquivo.txt

#### Comitar vários arquivos

	git commit meu_arquivo.txt meu_outro_arquivo.txt
	
#### Comitar informando mensagem

	git commit meuarquivo.txt -m "minha mensagem de commit"



----------------------------------------------------------------	

## Remover arquivo/diretório
### Remover arquivo

	git rm meu_arquivo.txt

##### Remover diretório

	git rm -r diretorio

-------------------------------------------------
## Ignorar Arquivos

Os nomes de arquivos/diretórios ou extensões de arquivos listados no arquivo **.gitignore** não serão adicionados em um repositório. Existem dois arquivos .gitignore, são eles:

* Geral: Normalmente armazenado no diretório do usuário do Sistema Operacional. O arquivo que possui a lista dos arquivos/diretórios a serem ignorados por **todos os repositórios** deverá ser declarado conforme citado acima. O arquivo não precisa ter o nome de **.gitignore**.

* Por repositório: Deve ser armazenado no diretório do repositório e deve conter a lista dos arquivos/diretórios que devem ser ignorados apenas para o repositório específico.	

-------------------------------------------------------------------

## Visualizar histórico
### Exibir histórico

	git log
	
### Exibir histórico com diff das duas últimas alterações

	git log -p -2
	
### Exibir resumo do histórico (hash completa, autor, data, comentário e qtde de alterações (+/-))

	git log --stat
	
### Exibir informações resumidas em uma linha (hash completa e comentário)

	git log --pretty=oneline
	
### Exibir histórico com formatação específica (hash abreviada, autor, data e comentário)

	git log --pretty=format:"%h - %an, %ar : %s"

	
* %h: Abreviação do hash;
* %an: Nome do autor;
* %ar: Data;
* %s: Comentário.

Verifique as demais opções de formatação no [Git Book](http://git-scm.com/book/en/Git-Basics-Viewing-the-Commit-History)

### Exibir histório de um arquivo específico

	git log -- <caminho_do_arquivo>

### Exibir histórico de um arquivo específico que contêm uma determinada palavra

	git log --summary -S<palavra> [<caminho_do_arquivo>]

 Exibir histórico modificação de um arquivo

	git log --diff-filter=M -- <caminho_do_arquivo>

* O <D> pode ser substituido por: Adicionado (A), Copiado (C), Apagado (D), Modificado (M), Renomeado (R), entre outros.

##### Exibir histório de um determinado autor

	git log --author=usuario

##### Exibir revisão e autor da última modificação de uma bloco de linhas

	git blame -L 12,22 meu_arquivo.txt 

--------------------------------------------------------------
### Desfazendo operações

##### Desfazendo alteração local (working directory)
Este comando deve ser utilizando enquanto o arquivo não foi adicionado na **staged area**. 

	git checkout -- meu_arquivo.txt

##### Desfazendo alteração local (staging area)
Este comando deve ser utilizando quando o arquivo já foi adicionado na **staged area**.

	git reset HEAD meu_arquivo.txt

Se o resultado abaixo for exibido, o comando reset *não* alterou o diretório de trabalho. 

	Unstaged changes after reset:
	M	meu_arquivo.txt

##### A alteração do diretório pode ser realizada através do comando abaixo:
	git checkout meu_arquivo.txt

----------------------------------------------------	
### Exibir os repositórios remotos

	git remote -v

### Vincular repositório local com um repositório remoto

	git remote add origin git@github.com:leocomelli/curso-git.git
	
### Exibir informações dos repositórios remotos

	git remote show origin
	
### Renomear um repositório remoto 

	git remote rename origin curso-git
	
### Desvincular um repositório remoto

	git remote rm curso-git

### Enviar arquivos/diretórios para o repositório remoto

O primeiro **push** de um repositório deve conter o nome do repositório remoto e o branch.

	git push -u origin master

	
Os demais **pushes** não precisam dessa informação

	git push
	
----------------------------------------------------------
### Atualizar repositório local de acordo com o repositório remoto
##### Atualizar os arquivos no branch atual

	git pull
	
##### Buscar as alterações, mas não aplica-las no branch atual

	git fetch
	
### Clonar um repositório remoto já existente

	git clone git@github.com:leocomelli/curso-git.git

-----------------------------------------------------------------------	
## Tags
### Criando uma tag leve

	git tag vs-1.1

##### Criando uma tag anotada

	git tag -a vs-1.1 -m "Minha versão 1.1"

##### Criando uma tag assinada
Para criar uma tag assinada é necessário uma chave privada (GNU Privacy Guard - GPG).

	git tag -s vs-1.1 -m "Minha tag assinada 1.1"

##### Criando tag a partir de um commit (hash)

	git tag -a vs-1.2 9fceb02
	
##### Criando tags no repositório remoto

	git push origin vs-1.2
	
##### Criando todas as tags locais no repositório remoto

	git push origin --tags

-----------------------------------------------------	
## Branches

O **master** é o branch principal do GIT.

O **HEAD** é um ponteiro *especial* que indica qual é o branch atual. Por padrão, o **HEAD** aponta para o branch principal, o **master**.

### Criando um novo branch

	git branch bug-123
	
##### Trocando para um branch existente

	git checkout bug-123
	
Neste caso, o ponteiro principal **HEAD** esta apontando para o branch chamado bug-123.

##### Criar um novo branch e trocar 

	git checkout -b bug-456
	
##### Voltar para o branch principal (master)

	git checkout master
	
##### Resolver merge entre os branches

	git merge bug-123
	
Para realizar o *merge*, é necessário estar no branch que deverá receber as alterações. O *merge* pode automático ou manual. O merge automático será feito em arquivos textos que não sofreram alterações nas mesmas linhas, já o merge manual será feito em arquivos textos que sofreram alterações nas mesmas linhas.

A mensagem indicando um *merge* manual será:

	Automerging meu_arquivo.txt
	CONFLICT (content): Merge conflict in meu_arquivo.txt
	Automatic merge failed; fix conflicts and then commit the result.


##### Apagando um branch

	git branch -d bug-123

###### Listar branches

	git branch

###### Listar branches com informações dos últimos commits

	git branch -v

###### Listar branches que já foram fundidos (merged) com o **master**

	git branch --merged

###### Listar branches que não foram fundidos (merged) com o **master**

	git branch --no-merged

###### Criando um branch remoto com o mesmo nome

	git push origin bug-123

###### Criando um branch remoto com nome diferente

	git push origin bug-123:new-branch

##### Baixar um branch remoto para edição

	git checkout -b bug-123 origin/bug-123

##### Apagar branch remoto

	git push origin:bug-123

-----------------------------------------------------
### Rebasing

Fazendo o **rebase** entre um o branch bug-123 e o master.

	git checkout experiment
	
	git rebase master
	

Mais informações e explicações sobre o [Rebasing](http://git-scm.com/book/en/Git-Branching-Rebasing)

--------------------------------------------------------

### Stash

Para alternar entre um branch e outro é necessário fazer o commit das alterações atuais para depois trocar para um outro branch. Se existir a necessidade de realizar a troca sem fazer o commit é possível criar um **stash**. O Stash como se fosse um branch temporário que contem apenas as alterações ainda não commitadas.

##### Criar um stash

	git stash
	
##### Listar stashes

	git stash list

##### Voltar para o último stash

	git stash apply

##### Voltar para um stash específico
	git stash apply stash@{2}
	
Onde **2** é o indíce do stash desejado.

##### Criar um branch a partir de um stash

	git stash branch meu_branch
--------------------------------------------------
## Lista de Procedimentos 

## Pull Request


## Criando uma Equipe
Diferente dos projetos que podem ser acessados a partir de outros contextos como organizações, usuários e repositórios. As equipes podems ser acessadas apenas através da organização à qual pertencem.

Entrando na página da organização podemos encontrar a opção do recursos de equipe no menu como mostrado no exemplo abaixo:

creating-by-organization

Logo em seguida veremos a opção de criar uma nova equipe abaixo do menu.

create-team-button

Agora veremos um formulário como mostrado abaixo:

create-team-form

Aqui é necessário informar o nome da equipe. Se necessário uma descrição e logo abaixo podemos escolher uma equipe primária caso exista. Ignore caso não tenha outra equipe para definir como primária ou caso simplesmente desconsidere necessário.

Como último passo é preciso informar a visibilidade da equipe. Isto é, definir como secreta caso a equipe seja privada. Assim apenas os membros da equipe poderão vê-la e pública caso julgue que não há razão para manter a equipe oculta.

Acabando de criar a equipe poderemos entrar na página de visualização:

team-page

Página inicial
A visualização inicial são as discussões existentes dentro da equipe. Esta visualização é muito útil para Avisos gerais, processos de idealização e instruções. Aqui todos os membros da equipe podem visualizar e participar.

Página de membros
team-members-page

Nesta página podemos ver todos os membros da equipe, agrupar a visualização por nível de permissão e caso tenha o nível requerido você pode gerenciar membros.


## Adicionando um membro à equipe
Nota 1: Observe que o nome de cada membro da equipe é um hyper texto(texto contendo um link) que ao ser clicado redireciona para a página da pessoa dentro da organização(que será detalhado no artigo 'Gestão de organizações com GitHub')

Na figura anterior é possível ver um botão verde para adicionar um membro. Ao clicar nele surgirá uma caixa de diálogo solicitando o nome de usuário, e-mail ou nome completo da pessoa que será adicionada. Basta informar uma dessas informações e surgirá uma lista abaixo da caixa de texto com o resultado da pesquisa baseada na informação inserida. Selecione o usuário que deseja e clique em Enviar. Agora a pessoa receberá uma notificação por e-mail e pode responder ao convite.

Nota 2: Podemos observar também que há um item de equipes no menu das equipes. Aqui é possível encontrar as equipes secundárias. Abordaremos este recurso em um artigo futuro.

Página de repositórios
Na página de repositórios veremos todos os repositórios dos quais as equipes fazem parte e outra vez, caso o usuário tenha o nível de acesso requerido poderá vincular um repositório à equipe. Para isto uma caixa de diálogo será exibida ao clicar no botão de adicionar repositório e ao informar o nome ou parte do caminho do repositório uma lista de resultados aparecerá onde é possível selecionar a opção desejada e salvar. Verifique o exemplo abaixo:

![link-repository-to-team](images/link-repository-to-team.jpg]

Página de projetos
Assim como a página de repositórios, esta página tem uma visualização para todos os projetos dos quais a equipe está vinculada.

Nota 3: No final deste artigo há uma referência para um artigo sobre a´Gestão de projetos com GitHub´.

Página de configurações
Por fim temos a página de configurações. Esta contém opções para deletar a equipe, modificar a visibilidade e também associação à outras equipes como descrito no momento da criação. Também é possível adicionar notificações agendadas através de vinculo com o Slack e opções de notificação para revisão de código.


## Reescrevendo o histórico
### Alterando mensagens de commit

	git commit --amend -m "Minha nova mensagem"

### Alterar últimos commits
Alterando os três últimos commits

	git rebase -i HEAD~3

O editor de texto será aberto com as linhas representando os três últimos commits.

	pick f7f3f6d changed my name a bit
	pick 310154e updated README formatting and added blame
	pick a5f4a0d added catfile

Altere para edit os commits que deseja realizar alterações.

	edit f7f3f6d changed my name a bit
	pick 310154e updated README formatting and added blame
	pick a5f4a0d added catfile

Feche o editor de texto.

Digite o comando para alterar a mensagem do commit que foi marcado como *edit*.

	git commit –amend -m “Nova mensagem”

Aplique a alteração

	git rebase --continue

**Atenção:** É possível alterar a ordem dos commits ou remover um commit apenas
mudando as linhas ou removendo.


## Juntando vários commits
Seguir os mesmos passos acima, porém marcar os commtis que devem ser juntados com **squash*
			
##### Remover todo histórico de um arquivo

	git filter-branch --tree-filter 'rm -f passwords.txt' HEAD
	
	
### Bisect

O bisect (pesquisa binária) é útil para encontrar um commit que esta gerando um bug ou uma inconsistência entre uma sequência de commits.

##### Iniciar pequinsa binária

	git bisect start
	
##### Marcar o commit atual como ruim

	git bisect bad

##### Marcar o commit de uma tag que esta sem o bug/inconsistência

	git bisect good vs-1.1

##### Marcar o commit como bom
O GIT irá navegar entre os commits para ajudar a indentificar o commit que esta com o problema. Se o commit atual não estiver quebrado, então é necessário marca-lo como **bom**.

	git bisect good

##### Marcar o commit como ruim
Se o commit estiver com o problema, então ele deverá ser marcado como **ruim**.

 	git bisect bad
 
##### Finalizar a pesquisa binária
Depois de encontrar o commit com problema, para retornar para o *HEAD* utilize:
	
	git bisect reset
 	

###  Contribuições

Sinta-se a vontade para realizar adicionar mais informações ou realizar correções. Fork me!


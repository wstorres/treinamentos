
#### ARTIGO <!--Obrigatorio-->

<SUB>[DATABASE](#) | [SQL](#) |<br /></SUB>
<sub>Por:<strong> Wagner Torres</strong> | Data: 23/09/2022</sub>

<img style="border-radius: 65px;" alt="" width="30" height="30" class="avatar avatar-user width-full border color-bg-default" src="https://avatars.githubusercontent.com/u/44095306?v=4">[<img src = "https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white">](https://github.com/wstorres)
___________________________________________
<!--INICIO DO PROJETO-->


<h2 align="center">O que é o Banco de Dados!</h2>
<!--(Obrigatorio)-->

## O que é o Banco de Dados e Suas Usabilidades

“Banco de dados” é um sitema capaz de coletar, armazenar e prover informações de consulta de dados.
No mundo digital, por exemplo, só está de pé porque nos bastidores da internet há inúmeros bancos de dados concectados capazes de processar e prover informações a todo momento.
Desde entrar em um site até fazer a compra de um produto em um e-commerce.
Tecnicamente, o Bando de Dados é um servidor físico que permite registrar diversas informações, como dados pessoais de clientes, tais como nome completo, endereço, data de nascimento, CPF e RG, entre outros itens que são utilizados para acompanhar a nossa base.

## Quais as diferenças entre dados e informações?

Os dados são informação bruta. Isso quer dizer que se tratam de um conjunto de elementos ainda não tratados. Um dado pode ser um conjunto de valores numéricos, estatísticos, entre outros. De modo isolado, um dado não possui um significado nítido.
Por outro lado, informações são dados compilados e analisados. Desse modo, os elementos que compõem uma informação possuem significados objetivos. Assim, podem ser utilizados como fonte de conhecimento e ajudar na tomada de decisão.

## O que são metadados?

Metadados são dados que definem outros conjuntos de dados. Toda informação que pode ser classificada e armazenada pode ser considerada um metadado. Esses tipos de dados são muito comuns no mundo digital, pois auxiliam softwares e hardwares a entenderem o relacionamento entre as informações.
Para compreendermos melhor o que são os metadados, vamos a um exemplo. Sempre que uma foto é feita utilizando a câmera de um smartphone, são gerados metadados. Nesse caso, o dado principal, a foto, será composta por outros dados, que apresentarão informações sobre o dispositivo utilizado, qual tipo de imagem foi gerada, sua data de criação, tamanho, entre outros.

Os metadados podem ser classificados em três categorias:

1. Estruturado: 
    
Que se liga a uma estrutura predefinida, como é o caso do exemplo da foto citado acima;

2. Não estruturado: 
    
Em que não há padronização, como um arquivo de texto, onde qualquer tipo de informação pode ser adicionada;

3. Semiestruturado: 

Um meio termo entre os dois anteriores. Uma estrutura pode ser definida, mas ainda assim podem ser recebidas informações diversas, como é o caso de um arquivo XML.

## Estrutura e evolução dos Bancos de Dados!
Bancos de dados são conjuntos de dados organizados e estruturados, em sua maioria dispostos em tabelas, que possuem linhas e colunas. Comumente, para controlar esses dados, é utilizado um sistema gerenciador de banco de dados. Além disso, para a consulta, criação e modificação das tabelas do banco, é utilizado o SQL, uma linguagem de consulta estruturada. 

O primeiro banco de dados foi lançado no início dos anos 1960. Na época, suas funcionalidades eram simples, porém inflexíveis, como é o caso do banco de dados hierárquico, que permitia apenas um relacionamento um-para-muitos. Nos anos 80, ganharam popularidade os bancos de dados relacionais, como resposta para a inflexibilidade dos primeiros modelos. 

Já nos anos 90, chegam os bancos orientados a objetos. Pouco tempo depois, surgem os bancos NoSQL, adaptados ao crescimento da internet e a necessidade de velocidade de processamento. Atualmente, o armazenamento na nuvem e os bancos de dados autônomos estão trazendo uma nova forma de armazenar, coletar e manipular dados.



## O que é a abstração de dados?
O sistema de gerenciamento de bancos de dados possui uma série de informações interligadas, desde os próprios dados a descrições sobre como as informações estão organizadas e armazenadas. 

Dessa forma, seria um desastre se qualquer pessoa usuária do sistema possuísse acesso a todos esses itens, uma vez que uma modificação incorreta poderia comprometer a estrutura do banco. 

Sendo assim, os SGBDs utilizam a abstração de dados. Isso significa que o sistema oculta determinados detalhes de suas informações, principalmente aquelas que impactam diretamente no funcionamento do sistema. A abstração de dados pode ser dividida em três níveis: o nível de visão, o lógico e o nível físico. Confira, a seguir, mais detalhes sobre essa divisão realizada pelos SGBDs. 

- Nível de visão do usuário
Nesse nível, parte do banco de dados real pode ser visualizado. Essa camada existe para facilitar a compreensão do banco pelas pessoas usuárias. Nesse caso, como os dados são armazenados não é algo relevante, bastando apenas que a pessoa usuária possa ver as informações e interagir com elas.

- Nível conceitual 
O nível conceitual é usado pelos sistemas gerenciadores de bancos de dados. Nessa camada, estão dispostas informações sobre como os dados estão relacionados. Trata-se de um nível intermediário.

- Nível físico
Esse é o nível de abstração mais baixo. No nível físico, ficam os detalhes mais complexos sobre como os dados são de fato armazenados e sobre como estão estruturados.


## Quais os desafios e desvantagens de usar um Banco de dados?

O uso de bancos de dados requer o suporte a um alto volume de consultas complexas e com uma velocidade de resposta instantânea. Dessa forma, vejamos adiante as principais barreiras que as bases de dados enfrentam atualmente:

1. Absorção de dados: a grande quantidade de informação disparada por sistemas e hardwares pode fazer com que as pessoas encarregadas da administração de bancos de dados fiquem sobrecarregadas, tentando entender qual a melhor forma de lidar com o gerenciamento.

2. Segurança: nenhum sistema está a salvo de invasões. Portanto, esta é mais uma preocupação que os sistemas de bancos de dados precisam lidar.

3. Demanda e manutenção: conforme a complexidade de consultas e o volume de dados cresce, as empresas precisam investir recursos para manter a base de dados funcional em relação à demanda exigida. 

4. Escalabilidade: prever a capacidade de um banco de dados enquanto a empresa cresce ainda é um desafio.

## Qual a relação entre Bancos de dados e Big data?

O Big Data é um banco de dados avançado. Nele, chegam uma variedade de dados complexos e em grandes volumes, em que um sistema de armazenamento tradicional não conseguiria gerenciar.

Com Big Data, é possível armazenar dados provenientes de mídias sociais, como vídeos e áudios. Além de haver a possibilidade de aplicar machine learning aos dados coletados, permitindo mineração e gerenciamento e análise autônoma das informações.

## Quais são as diferenças entre Big data e Data Analytics?

Data Analytics, assim como o Big data, é um banco de dados que recebe grande quantidade de informações complexas. Entretanto, no Data Analytics, esses dados são utilizados como objeto de análise em um foco específico. 

Desse modo, no mercado de trabalho, uma pessoa analista de dados pode utilizar o Data Analytics para obter respostas sobre um problema específico, como a relação entre horários de produção e o volume produzido em uma empresa, por exemplo.

<!--FIM DO PROJETO-->
_________________________________________



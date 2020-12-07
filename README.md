# Projeto-Trabalho-de-Graduacao-em-Banco-de-Dados-I - 5º BD

Professor da Disciplina: Giuliano Bertoti

Aluno: Andre de Souza Andrade Pires

RA: 1460281823005

## 1. INTRODUÇÃO 

Infelizmente, na sociedade em que nós vivemos ainda existe uma desigualdade muito grande entre as pessoas de diferentes classes sociais. Com isso é necessário que hajam projetos que auxiliam e trabalhem na inclusão de pessoas desprivilegiadas para que essa desigualdade diminua e quem sabe um dia se extinguir. Com isso uma condição melhor de vida seria possível para o grande número de pessoas que estão nesta situação no Brasil, onde a grande maioria delas já nasce com inúmeras desvantagens.

Um bom exemplo relacionado a esse assunto são com jovens meninas, principalmente crianças e adolescentes, onde a personalidade e caráter ainda não se estabeleceram completamente ainda. Essas pessoas cuja desigualdade social impõe muitas dificuldades sobre suas vidas muitas vezes escolhem o caminho onde conflitos com a lei acontecem e com isso, a volta à sociedade torna-se ainda mais difícil do que já era, o que as exclui cada vez mais[1].

Referente ao assunto tocado anteriormente entra o instituto Mundo Aflora, um instituto que visa oferecer oportunidades para que as adolescentes possam fazer novas escolhas, oferecendo a reintegração dessas jovens que estão ou estiveram em privação de liberdade.

Com base no que foi dito acima, foi feito a plataforma ConectAflora, que visa facilitar esse trabalho feito pelo instituto Mundo Aflora por meio de uma plataforma online.


### 1.1. Objetivos

O objetivo do projeto foi a criação de uma plataforma online parecida com uma rede social para conexões profissionais. As pessoas com interesse de ajudar com a inclusão social de jovens ligadas ao instituto Mundo Aflora possam oferecer vagas de trabalhos e mentoria para as jovens.

A plataforma contaria com a construção de perfis tanto para as jovens quanto para as pessoas voluntárias que oferecerão vagas de de trabalhos e mentoria. Além disso, a plataforma ofereceria um auxílio, uma forma de orientação vocacional onde seria coberto instruções para a elaboração de um currículo virtual. Com base neste currículo seriam ligados ao perfil das jovens tags que teriam a função de tentar direcionar a jovem a uma área que corresponda com suas características e habilidades presentes em seu currículo e perfil.

Com estas tags, um sistema de “match” ocorrerá ligando vagas de emprego onde a jovem possivelmente se encaixe melhor.


## 2. FUNDAMENTAÇÃO TÉCNICA 

Grande parte do projeto está relacionado com a ciência de dados junto com o uso de tags para as recomendações e o sistema de “match” que a plataforma irá fazer. Além disso, também inclui uma boa usabilidade e não menos importante a segurança da informação dos usuários cadastrados na plataforma.

### 2.1. Ciência de Dados e uso de tags para recomendações 

Um estudo conduzido em 2010 por Guy, Zwerdling, Ronen, Carmel e Uziel[2] demonstrou que o uso de tags pode ser muito eficiente para formulação de recomendações, pois estas se traduzem em melhores filtros para tópicos de interesse. 

### 2.2. Usabilidade  

Visto que devido a situação das jovens ligadas ao projeto, elas provavelmente não teriam um contato muito grande com as tecnologias atuais, portanto a plataforma teria um foco
bem grande na usabilidade para que nada dificulte a aprendizagem das jovem ao usar a plataforma.

### 2.3. Segurança da informação 

Considerando o volume e a sensibilidade dos dados que serão transitarão pela plataforma, normas de segurança de dados deverão ser aplicadas para garantir o cumprimento da legislação vigente.

## 3. DESENVOLVIMENTO

A aplicação será construída no formato Progressive Web App (PWA), e utilizará arquitetura REST combinada a um framework frontend que garanta alta usabilidade. 

### 3.1. Progressive Web App (PWA) 

Progressive Web App (PWA) é uma metodologia de desenvolvimento de software que combina recursos de navegadores com os benefícios de aplicações para dispositivos móveis. 

Desta forma, buscamos garantir que a plataforma possa ser acessada com a devida fluidez por qualquer dispositivo, sem necessidade de instalação de aplicativo específico. 

### 3.2. Arquitetura REST 

Conforme mencionado por Thiago Berlitz Rondon, REST (Representational State Transfer ou Transferência de Estado Representacional) é estilo de arquitetura de software sobre um sistema operado em rede, que vê cada aplicação web como um conjunto de recursos, que representam um estado particular de um aplicativo. Quando você acessa este recurso, Rondon continua, você está transferindo o estado (conteúdo), e talvez alterando o seu estado [3]. 

A aplicação será baseada nesta modalidade de arquitetura, que será consumida pelo servidor de frontend. 

### 3.3 DevOps

O projeto contará com a implementação de um sistema DevOps. Esse sistema ajuda a agilizar e facilitar os processos necessários para a implantação de um sistema para o ambiente de produção para que o valor ao usuário seja gerado.

A adoção das praticas DevOps apresentam um alto desempenho, fazendo com que a criação do produto seja melhor e mais rapido.

## REFERÊNCIAS  

[1]MACHADO CELLA, Silvana; POMPÊO DE CAMARGO, Dulce Maria. Trabalho pedagógico com adolescentes em conflito com a lei: feições da exclusão/inclusão Educação & Sociedade, vol. 30, núm. 106, enero-abril, 2009, pp. 281-299 Centro de Estudos Educação e Sociedade Campinas, Brasil. Disponível em https://www.redalyc.org/pdf/873/87313703014.pdf Acesso em 06/12/2020. 

[2]GUY, Ido; ZWERDLING, Naama; RONEN, Inbal; CARMEL, David; UZIEL, Erel. Social Media Recommendation based on People and Tags. IBM Research Lab, Haifa 31905, Israel, out. 2010. 

[3]RONDON, Thiago Berlitz. Arquitetura REST e o serviço web 'RESTful'. Publicado em 01/01/2010. Disponível http://sao-paulo.pm.org/pub/arquitetura-rest-e-o-servico-web-restful-. Acesso em 06/12/2020. 

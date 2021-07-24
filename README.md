<!-- Visualizador online: https://stackedit.io/ -->
 ![Logo da UDESC Alto Vale](http://www1.udesc.br/imagens/id_submenu/2019/marca_alto_vale_horizontal_assinatura_rgb_01.jpg)

---


Trabalho realizado para a disciplina de Inteligência Computacional do [Centro de Educação Superior do Alto Vale do Itajaí (CEAVI/UDESC)](https://www.udesc.br/ceavi)<br>O objetivo do trabalho é implementar alguma técnica de Inteligência Computacional para demonstrar sua aplicação. A técnica de Inteligência Computacional que será utilizada no trabalho será alguns algoritmos de sistemas de recomendação, abaixo irie explicar os algoritmos que serão implementados. 



# Sumário 
* [Equipe](#equipe)
* [Problema](#problema)
* [Dataset](#dataset)
* [Técnicas](#tecnicas)
* [Resultados](#resultados)
* [Instruções de Uso](#instrucao)
* [Vídeo](#video)



---

## [Equipe](#equipe)
 - [**Robson de Jesus**](mailto:robson.jesus@edu.udesc.br) - [robsondejesus1996](https://github.com/robsondejesus1996)


## [Problema](#problema)


---

## [Dataset](#dataset)

A dataset utilizado foi foi coletado no site www.adorocinema.com esse site das as informações dos principais filmes e séries da atualizadade, nele podemos verificar as notas que usuários pré-cadastrados informam para os principais filmes e series. Foi utilizado sete usuários fictícia para formar o dataset de filmes, e o usuário "Robson" que será o principal estudo de caso nos algoritmos testados.<br>
Os dados são formados por geralmente seis filmes em cada objeto "Pessoa" existem pessoas que não assistiram alguns filmes, logo o nome e a nota não estara disponível no objeto. Por exemplo o Robson que é o principal estudo da base não assistiu alguns filmes, então para fazer a recomendação de um filme o primeiro passo é que o usuário estudado não tenha assistido aquele filme. 


**Dataset de avaliações**
<h1>Avaliações objetos</h1>

| Nome  |  Freddy x Jason  | O Ultimato Bourne | Star Trek | Exterminador do Futuro | Norbit | Star Wars
| ------------------- | ------------------- |------------------- | ------------------- | ------------------- | ------------------- | ------------------- |
|  Luiz |  2.5 | 3.5 | 3.0  | 3.5 |  2.5  | 3.0 
|  Caio |  3.0 | 3.5 | 1.5  | 5.0 |  3.0  | 3.5 
|  Brenda |  2.5 | 3.0 | x  | 3.5 |  x  | 4.0 
|  Aline |  x | 3.5 | 3.0  | 4.0 |  2.5  | 4.5 
|  Jean |  3.0 | 4.0 | 2.0  | 3.0 |  2.0  | 3.0 
|  Jasmin |  3.0 | 4.0 | x  | 5.0 |  3.5 | 3.0 
|  <b>Robson</b> |  x | 4.5 | x | 4.0 |  1.0  | x 


avaliacoes = {'Luiz':
                  {'Freddy x Jason': 2.5,
                   'O Ultimato Bourne': 3.5,
                   'Star Trek': 3.0,
                   'Exterminador do Futuro': 3.5,
                   'Norbit': 2.5,
                   'Star Wars': 3.0},

              'Caio':
                  {'Freddy x Jason': 3.0,
                   'O Ultimato Bourne': 3.5,
                   'Star Trek': 1.5,
                   'Exterminador do Futuro': 5.0,
                   'Star Wars': 3.0,
                   'Norbit': 3.5},

              'Brenda':
                  {'Freddy x Jason': 2.5,
                   'O Ultimato Bourne': 3.0,
                   'Exterminador do Futuro': 3.5,
                   'Star Wars': 4.0},

              'Aline':
                  {'O Ultimato Bourne': 3.5,
                   'Star Trek': 3.0,
                   'Star Wars': 4.5,
                   'Exterminador do Futuro': 4.0,
                   'Norbit': 2.5},

              'Jean':
                  {'Freddy x Jason': 3.0,
                   'O Ultimato Bourne': 4.0,
                   'Star Trek': 2.0,
                   'Exterminador do Futuro': 3.0,
                   'Star Wars': 3.0,
                   'Norbit': 2.0},

              'Yasmin':
                  {'Freddy x Jason': 3.0,
                   'O Ultimato Bourne': 4.0,
                   'Star Wars': 3.0,
                   'Exterminador do Futuro': 5.0,
                   'Norbit': 3.5},

              'Robson':
                  {'O Ultimato Bourne': 4.5,
                   'Norbit': 1.0,
                   'Exterminador do Futuro': 4.0}
              }


---
## [Técnicas](#tecnicas)

<h1>Recuperação direta da Informação</h1>

<p>Em sistemas que são baseados na recuperação direta da informação, o usuário seleciona a informação ou a descreve com palavras-chave, sendo que uma consulta é enviada ao sistema que logo após retorna os itens que correspondem à pesquisa. Esse método é um dos mais simples devido a sua objetividade, porém, para que esse tipo de sistema funcione satisfatoriamente, os conteúdos devem estar estruturados e organizados em um banco de dados.</p>

<h1>Filtragem por Conteúdo</h1>

<p>A filtragem baseada em conteúdo ocorre em informações sobre o conteúdo dos itens e sobre o perfil do usuário, sendo essas informações normalmente textuais. Ela consiste de algoritmos de aprendizagem de máquina supervisionados para gerar automaticamente a descrição dos itens e assim compará-los com o perfi</p>

<h1>Filtragem Coloborativa</h1>

<p>A recomendação via filtragem colaborativa baseada em memória é fundamentada pelo comportamento dos usuários no passado. Em outras palavras, é baseada na similaridade de preferências, gostos e escolhas entre usuários ao longo do tempo. Ela analisa o quão semelhante o gosto de um usuário é para o outro e faz recomendações com base nisso.</p>



---

## [Resultados](#resultados)

---

## [Instruções de Uso](#instrucoes)

---

## [Vídeo](#video)
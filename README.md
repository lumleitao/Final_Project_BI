# Final-Project-BI
Projeto final do curso de Business Intelligence - PUC RIO
Produtos Ferrero - Analise de Desempenho
Aluno: Luana Martins Leitao
Orientadora: Anderson Nascimento
Trabalho apresentado ao curso BI MASTER como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

Resumo

Este documento tem por objetivo coletar, analisar e definir as principais necessidades do projeto do estudo de caso " Produtos Ferrero - Analise de Desempenho ". Nele, busca-se identificar os principais produtos consumidos pelos funcionarios em cada localidade, com o intuito de avaliar possiveis açoes de marketing e descontos que possam impulsionar e maximizar as vendas.

Abstract

A Ferrero é uma empresa italiana de confeitaria reconhecida mundialmente pela alta qualidade de seus produtos. A empresa foi fundada em 1946 na cidade de Alba - Italia, na regiao de Piemonte, e o que começou como uma pequena confeitaria familiar, logo se tornou uma das maiores fabricantes de chocolates e doces do mundo.

Conhecida por suas marcas iconicas tais como Nutella, Ferrero Rocher, Kinder e Tic Tac, seus produtos conquistaram consumidores de todas as faixas etarias. Atualmente a Ferrero atende mais de 170 paises, expandindo sua presença global dia apos dia, sem perder seus valores familiares. E como parte de seu comprometimento com a comunidade local, a Ferrero construiu pequenas lojas dedicada aos funcionarios de suas fabricas, para que eles possam se beneficiar de descontos e preços de custo de seus produtos.

O projeto visa realizar uma analise detalhada do desempenho de vendas de tres lojas dedicadas as funcionarios, com o objetivo de identificar as tendencias, oportunidades de melhoria e possiveis açoes de marketing para maximizar as vendas.

1. Introdução
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin pulvinar nisl vestibulum tortor fringilla, eget imperdiet neque condimentum. Proin vitae augue in nulla vehicula porttitor sit amet quis sapien. Nam rutrum mollis ligula, et semper justo maximus accumsan. Integer scelerisque egestas arcu, ac laoreet odio aliquet at. Sed sed bibendum dolor. Vestibulum commodo sodales erat, ut placerat nulla vulputate eu. In hac habitasse platea dictumst. Cras interdum bibendum sapien a vehicula.

Proin feugiat nulla sem. Phasellus consequat tellus a ex aliquet, quis convallis turpis blandit. Quisque auctor condimentum justo vitae pulvinar. Donec in dictum purus. Vivamus vitae aliquam ligula, at suscipit ipsum. Quisque in dolor auctor tortor facilisis maximus. Donec dapibus leo sed tincidunt aliquam.

2. Modelagem
A modelagem multidimensional utilizada no projeto é o modelo estrela, amplamente utilizado em soluçoes de Business Intelligence (BI) para analise e visualizaçao de dados. Essa abordagem organiza as informaçoes em duas categorias principais: fatos e dimensoes.

Estrutura do Modelo

1. Fato Principal

Contem as metricas quantitativas, tais como:

Quantidade vendida

Valor da venda

Faturamento total

Ticket medio

2. Dimensoes

O modelo estrela conecta a tabela de fatos com as tabelas dimensionais, permitindo analises flexiveis. E as principais dimensoes identificadas no projeto incluem:

Produto: codigo do produto, descriçao e categoria.

Vendedor: nome do vendedor e informaçoes associadas.

Loja: codigo e localizaçao

Tempo: data das vendas organizadas em ano, mes e dia.

3. Chaves de relacionamento

Como cada dimensao possui uma chave primaria que se relaciona com a chave estrangeira correspondente na tabela de fatos, foi possivel entao ligar o codigo do produto na dimensao produto e conecta-la ao codigo do produto na tabela fato por exemplo.

A modelagem foi implementada no Power BI, utilizando o modelo estrela para criar um dashboard interativo, onde os usuarios podem aplicar filtros nas dimensoes (por exemplo, ano, loja, produto) e explorar insights diretamente a partir das metricas calculadas.

3. Resultados
Atraves do dashboard desenvolvido, foi possivel identificar as tendencias de consumo e entender as preferencias dos consumidores, desenvolvendo estrategias de marketing e promoçoes direcionadas ao publico alvo. A facilidade na visualizaçao dos dados permitiu aos diretores e gestores acessar de forma pratica e intuitiva as informaçoes, permitindo aumentar a rapidez na tomada de decisao.

4. Conclusões
O projeto final foi uma excelente oportunidade de estabelecer todo o processo de utilizaçao do Power BI de forma convencional, alem de implementar essa abordagem no meu trabalho atual, proporcionando maior visibilidade para as partes interessadas. Com base neste projeto, os diretores conseguem obter informaçoes de maneira rapida e intuitiva, possibilitando a criaçao de planos de açao mais eficazes e bem fundamentados.

O cliente demonstrou grande satisfaçao e ficou surpreso com a proatividade e conhecimento tecnico apresentados durante o projeto, o que elevou o nivel de profissionalismo e destacou minha atuaçao na area.

Matrícula: 221.101.067

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação Business Intelligence Master

# Construição de um modelo de Machine Learning para previsão dos valores de imoveis.

-----
para ver o código em python completo via colab:
* <a href="https://colab.research.google.com/drive/13DNHx-BtuYff0rSDf0aJycX9-7PajYRX?usp=sharing" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

-----

 ###### Contexto analítico:

Nesse desafio, você deve resolver um case de precificação de imóveis. Esse desafio foi construído em parceria entre a Tera e o QuintoAndar, onde o objetivo é simular um projeto de machine learning com características semelhantes ao que ocorre no dia a dia da empresa.

Imagine-se na seguinte situação: a área de marketing do QuintoAndar quer montar uma calculadora de preço (como esta [aqui: https://mkt.quintoandar.com.br/quanto-cobrar-de-aluguel/), e nesse projeto, os analistas negociais e corretores querem, também, entender as principais variáveis e características chaves que influenciam no valor de venda do imóvel (Ex: quantificar o impacto do aumento da área do imóvel no preço, ou quantificar o impacto de ter piscina, ou não no preço). Você é o cientista de dados que atuará na resolução desse case.

Para tanto, existem dois objetivos principais:

Objetivo 1, interpretabilidade: construir uma regressão linear simples, com poucas variáveis importantes, visando gerar insights para corretores e proprietários no quesito precificação dos imóveis. Ou seja, o foco será na interpretação dos coeficientes (ex: se aumentar a área do imóvel em uma unidade isso irá aumentar em Y o preço deste imóvel).

Objetivo 2, predição: construir um modelo com alto poder preditivo, com mais variáveis, visando um bom desempenho e com o intuito de ser usado em uma página web como a calculadora de preço. Note que, em uma situação real, um alto erro de inferência pode gerar grande insatisfação em um proprietário de imóvel, que pode ficar ofendido com o resultado. Por isso, em casos como esse, queremos ter o menor erro possível, mesmo que o modelo  seja complexo e tenha uma interpretação mais difícil.

 Base de dados 

O conjunto de dados descreve a venda de propriedades residenciais individuais de uma cidade americana, de 2006 a 2010. O conjunto de dados contém 2.930 observações e um grande número de features (23 nominais, 23 ordinais, 14 discretas e 20 contínuas) envolvidas na avaliação do valor dos imóveis, ou seja, são 80 variáveis explicativas.

Geralmente, as 20 features ​​contínuas estão relacionadas com várias dimensões de área para cada imóvel. Além do típico tamanho do lote e da metragem quadrada total da área habitável, outras variáveis ​​mais específicas são quantificadas no conjunto de dados. Medidas da área do porão, área da sala de estar e até mesmo das varandas estão presentes e divididas em categorias individuais com base na qualidade e no tipo. O grande número de variáveis ​​contínuas neste conjunto de dados deve fornecer muitas oportunidades de discretização e construção de novas features. 

As 14 features ​​discretas normalmente quantificam o número de itens que existem na casa. Como, por exemplo: o número de cozinhas, quartos e banheiro discretizados por sua localização (porão ou acima do térreo). Adicionalmente, a capacidade da garagem e as datas de construção/reforma também estão registadas.

As features ​​nominais normalmente identificam várias categorias de moradias, garagens, materiais e condições ambientais, enquanto as variáveis ​​ordinais normalmente classificam vários itens na propriedade. 

# Conclusão


Foi realizado uma analise exploratoria de dados junto a um modelo de regressão multipla e em seguida todo o pré processamento, pipeline, baseline do banco de dados afim de construir um modelo de Machine Learning para realizar a previsão dos valores de imoveis e em seguida, realizando a computação dos resultados,  e assinado pela empresa Quinto Andar.

Existe algumas aberturas para se aprofundar ainda mais em relação a features de interesse, podendo assim, melhorar ainda mais o modelo.

As Features de interesse que foram escolhidas, são a "Area Construida", "Area Garagem", "Total Quartos", "Condição", "Qualidade" e "Bairro", por conta de ter uma significancia muito grande para ser estimado o valor do imovel. 

conforme foi surgindo mudanças no modelo, eu irei atualizar o aquirvo .ipynd

***A proposta do projeto foi dada por um experd da Tera e assinado pela empresa Quinto Andar.***

----
# Agradecimentos

Deixo aqui a minha nota de agradecimento para todos os meus colegas, facilitadores e experds do curso de Data Science & Machine Learning na Tera
----

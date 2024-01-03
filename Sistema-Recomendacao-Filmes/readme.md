
# Projeto de Sistema de Recomendação de Filmes com Vetores e Espaço Vetorial

## Objetivo

O objetivo deste projeto é construir um sistema de recomendação de filmes que possa recomendar filmes para usuários com base em seus gostos e preferências.

## Metodologia

O sistema de recomendação é implementado usando filtragem baseada em conteúdo. Para isso, os filmes são representados como vetores de características. As características dos filmes incluem o título, gênero, o diretor, os atores, e algumas tags que se relacionam com o filme.

A similaridade entre dois filmes é calculada usando o produto escalar e distância entre vetores, mais especificamente a distância de similaridade de coseno. Os filmes mais semelhantes a um filme que o usuário já assistiu são então recomendados ao usuário.

## Dados

Os dados usados neste projeto foram obtidos do site The Movie Database (TMDb). Os dados incluem informações sobre filmes, como o título, o gênero, o diretor, os atores, a avaliação do público e a avaliação da crítica, mas uma engenharia de atributos foi realizada para selecionar as features mais relevantes para o projeto.

## Resultados

O sistema de recomendação não foi avaliado com uma métrica específica, mas se mostrou muito preciso ao recomendar filmes bastante similares ou ao título ou ao gênero do filme que o usuário indica. É possível aprimorar o sistema, mas esse não foi o foco do projeto, que teve uma intenção mais didática e de experimentação.

## Conclusão

O sistema de recomendação implementado neste projeto é capaz de recomendar filmes com bastante precisão. Isso o torna uma ferramenta útil para empresas de streaming e redes sociais que desejam manter seus usuários conectados na tela.

## Como usar

Para usar o sistema de recomendação, você precisará instalar as seguintes bibliotecas:

nltk
numpy
pandas
scikit-learn

Depois de instalar as bibliotecas, você pode executar o código no arquivo Projeto_Sistema_de_Recomendação_de_Filmes.ipynb no Google Colab ou VS Code. 
Carregue os arquivos dataset_elenco e dataset_filmes para o ambiente e copie o caminho na chamada do pd.read_csv usando UTF-8 como encoding.

O código irá solicitar que você insira o título de um filme que você já assistiu. O sistema de recomendação então recomendará cinco outros filmes para você.

## Referências

**The Movie Database (TMDb)**: https://developer.themoviedb.org/docs: https://developer.themoviedb.org/docs

**Filtragem baseada em conteúdo**: https://en.wikipedia.org/wiki/Content-based_filtering: https://en.wikipedia.org/wiki/Content-based_filtering

**Produto escalar**: https://en.wikipedia.org/wiki/Dot_product: https://en.wikipedia.org/wiki/Dot_product

## Próximos passos:
Usar mais características para representar os filmes.

Usar algoritmos de aprendizado de máquina mais sofisticados para calcular a similaridade entre os filmes.

Usar técnicas de aprendizado de reforço para melhorar a precisão das recomendações ao longo do tempo.

# O que são Sistemas de Recomendação?

Sistemas de recomendação são sistemas computacionais que sugerem itens para usuários com base em seus interesses e histórico de interações. Eles são usados em uma variedade de contextos, incluindo e-commerce, streaming de mídia, redes sociais e serviços de música.

Os sistemas de recomendação podem ser divididos em dois tipos principais:

**Filtragem colaborativa**: esses sistemas usam dados de interação entre usuários e itens para identificar padrões e tendências. Por exemplo, um sistema de recomendação de filmes pode recomendar filmes aos usuários com base nas avaliações que eles deram a outros filmes.

**Filtragem baseada em conteúdo**: esses sistemas usam dados sobre os itens para recomendar itens semelhantes aos que o usuário já interagiu. Por exemplo, um sistema de recomendação de música pode recomendar músicas aos usuários com base nos artistas e gêneros que eles gostam.

Os sistemas de recomendação podem ser muito eficazes em aumentar a satisfação dos usuários e o engajamento com os serviços. Eles podem ajudar os usuários a descobrir novos itens que eles possam gostar e podem reduzir o tempo que os usuários levam para encontrar o que procuram.

Aqui estão alguns exemplos de sistemas de recomendação:

**Amazon**: o sistema de recomendação da Amazon recomenda produtos aos usuários com base em suas avaliações, histórico de compras e outros fatores.

**Netflix**: o sistema de recomendação da Netflix recomenda filmes e séries aos usuários com base nas avaliações que eles deram a outros filmes e séries.

**Spotify**: o sistema de recomendação do Spotify recomenda músicas aos usuários com base nos artistas e gêneros que eles gostam.



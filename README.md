# - RecomendaFilmesPython

# Sistema de Recomendação de Filmes

Este é um sistema simples de recomendação de filmes baseado em filtragem colaborativa usando o algoritmo KNN (K-Nearest Neighbors). Ele utiliza dados de avaliações de filmes por usuários para sugerir filmes semelhantes aos que o usuário gosta.

#Requisitos
Certifique-se de ter instalado os seguintes pacotes:

pandas
numpy
scipy
scikit-learn

# Você pode instalá-los executando:
pip install pandas numpy scipy scikit-learn

# Como funciona

-Coleta de Dados: Os dados são carregados a partir de duas planilhas Google contendo informações sobre filmes e avaliações de usuários.

-Pré-processamento de Dados: Os dados são filtrados e limpos para remover filmes com poucas avaliações, filmes em idiomas diferentes de inglês e usuários com menos de 1000 avaliações.

-Construção do Modelo: Uma matriz esparsa é construída usando a tabela pivô das avaliações dos filmes por usuários. O algoritmo KNN é treinado usando esta matriz para encontrar os filmes mais semelhantes com base nas avaliações dos usuários.

-Recomendação de Filmes: O usuário é solicitado a inserir o nome de um filme. O sistema verifica se o filme está na base de dados e, se estiver, sugere outros filmes semelhantes com base nas avaliações dos usuários.

#Como usar

Execute o script Python recommendation_system.py.
Siga as instruções na linha de comando para inserir o nome de um filme.
O sistema irá sugerir outros filmes semelhantes com base na entrada do usuário.

#Notas
Certifique-se de que as planilhas Google contêm os dados corretos e estão acessíveis.
Este sistema de recomendação é apenas para fins educacionais e pode ser aprimorado com mais técnicas e dados adicionais.



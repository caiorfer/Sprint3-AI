U.R.S.A - Book Recommendation System
Descrição do Projeto
U.R.S.A (Unity of Resolutions for Softwares and Applications) é um sistema de recomendação de livros desenvolvido para uma startup de e-commerce. O objetivo principal do sistema é aumentar o engajamento e a satisfação dos clientes por meio de recomendações personalizadas, baseadas nas avaliações fornecidas por outros usuários.

Este sistema inicial utiliza dados fictícios para demonstrar um modelo básico de recomendação baseado na média das avaliações. Ele foi desenvolvido em Python, utilizando a biblioteca Pandas para manipulação de dados, e pode ser executado no Google Colab ou em ambientes locais.

Objetivo Principal
Desenvolver uma solução de recomendação para uma plataforma de e-commerce de livros.
Aprimorar a experiência do usuário oferecendo sugestões personalizadas de livros.
Funcionalidades
Recomendação por Média de Avaliações: O sistema calcula a média de avaliação de cada livro com base nas notas dos usuários e recomenda os melhores avaliados.
Análise de Dados: Visualização inicial dos dados de livros, usuários e avaliações.
Organização e Estrutura do Repositório
O projeto está organizado nas seguintes pastas e arquivos:

data/: Contém os arquivos CSV com dados de exemplo, incluindo:

livros.csv: Dados dos livros com ID, título e autor.
usuarios.csv: Dados dos usuários, como idade e gênero.
avaliacoes.csv: Dados das avaliações, com ID do usuário, ID do livro e a avaliação numérica.
src/: Contém o código Python necessário para carregar, processar e gerar as recomendações. O código inclui:

Carregamento dos dados dos arquivos CSV.
Cálculo da média de avaliações por livro.
Organização dos livros por avaliação para recomendação dos melhores avaliados.
README.md: Documento de descrição do projeto, com instruções e explicações detalhadas.

Pré-requisitos e Configuração do Ambiente
Para rodar o projeto, você precisará dos seguintes requisitos:

Python: Versão 3.6 ou superior.
Biblioteca Pandas: Para instalar, use pip install pandas.
Google Colab (opcional): A plataforma recomendada para executar o projeto, especialmente se não tiver um ambiente local configurado.
Configuração no Google Colab
Upload dos Dados: Carregue os arquivos CSV da pasta data/ para o Google Colab.
Execução do Código: Importe e execute os scripts Python da pasta src/.

Guia de Uso
Carregamento dos Dados: O código carrega e exibe os dados dos arquivos livros.csv, usuarios.csv, e avaliacoes.csv, proporcionando uma visão inicial das informações disponíveis.

Cálculo da Média de Avaliações: As avaliações são agrupadas por livro e a média é calculada, criando uma tabela de livros com suas médias de avaliações.

Geração de Recomendação: O sistema organiza os livros de acordo com a média das avaliações e exibe uma lista dos livros mais recomendados, com base nas notas dadas pelos usuários.

Estrutura do Código e Explicação
O código segue os seguintes passos principais:

Criação dos DataFrames: Os dados dos livros, usuários e avaliações são lidos dos arquivos CSV e armazenados em DataFrames usando o Pandas.

Cálculo da Média de Avaliações: As avaliações dos livros são agrupadas e a média é calculada. Esta média é associada ao ID de cada livro.

Recomendação e Ordenação: O DataFrame é mesclado com o DataFrame dos livros para associar os títulos e autores aos IDs. Em seguida, os livros são ordenados do mais bem avaliado para o menos bem avaliado.

Contribuidores
Caio Rocha Fernandes
Florbela Freitas Oliveira
Jaquelline Aparecida C. B. de Sousa 

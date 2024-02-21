# Azure-Cognitive-Search
Utilizando AI Search para indexação e consulta de Dados

Neste exemplo vamos criar uma solução de mineração de conhecimento que facilite a pesquisa de insights sobre as experiências do cliente, criando um índice de Pesquisa de IA do Azure e usando dados extraídos de avaliações de clientes para criar insghts sobre suas experiências.

Para tanto usaremos os seguintes passos:

__1 - Criar recursos do Azure necessários__

+ Recurso de Pesquisa de IA do Azure
+ Recurso de serviços de IA do Azure
+ Conta de armazenamento

[Para mais detalhes clique aqui.](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html#azure-resources-needed)

__2 - Carregar documentos no Armazenamento do Azure__

[Para mais detalhes clique aqui.](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html#upload-documents-to-azure-storage)


__3 - Indexar os documentos__

Depois de ter os documentos em armazenamento, poderemos usar o Azure AI Search para extrair insights dos documentos. O portal do Azure fornece um assistente de Importação de dados. Com esse assistente, criaremos automaticamente um índice e um indexador para fontes de dados com suporte. usaremos o assistente para criar um índice e importar seus documentos de pesquisa do armazenamento para o índice de Pesquisa de IA do Azure.

[Para mais detalhes clique aqui.](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html#index-the-documents)


__4 - Consultar o índice__

Usaremos o Gerenciador de pesquisa para escrever e testar consultas. O explorador de pesquisa é uma ferramenta incorporada no portal do Azure que oferece uma maneira fácil de validar a qualidade do índice de pesquisa. Poderemos usar o Gerenciador de pesquisa para escrever consultas e revisar resultados em JSON.

Abaixo do índice selecionado, altere a exibição para JSON view, 

![imagem original](/inputs/search.png)


Revisar o repositório de conhecimento
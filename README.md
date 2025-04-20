# Alura Stores

## Project Overview
Este projeto proposto pela Alura LATAM tem como objetivo praticar o uso de python em um cenário de data science. O contexto se trata de um empresário fictício que deseja a venda de uma de suas 4 lojas. Com dados em formato csv para cada uma das lojas, a análise deve apresentar uma sugestão final de qual(is) loja(s) vender e porque, além de apresentar 3 gráficos para análise visual.

Breves comentários em python foram inseridos em cada bloco de código para explicar sua função. Abaixo deixo um passo a passo de como acessar o arquivo com o Google Colab.

## Estrutura do Projeto
Desenvolvido em Python, você pode abrir os arquivos em qualquer leitor que suporte Jupyter Notebooks, como o Visual Studio Code, por exemplo. Realize a interação com o programa de sua preferência.

## Exemplos de Gráficos e Insights Obtidos
Durante a análise dos dados vistos no arquivo, você perceberá alguns gráficos que ajudarão a entender o caminho que os insights tomaram. Abaixo seguem os gráficos gerados durante a análise:

### Faturamento por Loja
Este gráfico mostra qual loja teve o maior faturamento dentre as 4. Vemos uma linha decrescente, mostrando que a loja 1 fatura mais, enquanto a loja 4 fatura menos. Mas... Será o faturamento sinônimo de bom desempenho?

![faturamento_por_loja](https://github.com/user-attachments/assets/7d450abc-2363-46b4-a265-909898bead47)

### Avaliação Média por Loja
Este gráfico mostra como as lojas foram avaliadas pelos clientes após a compra, em média. Claro, a avaliação não é a única forma de estudar o desempenho da loja, mas lembremo-nos da máxima "O cliente tem sempre razão". Assim, vemos que o faturamento mascarou uma média de avaliação um tanto baixa em relação à loja 1. Enquanto a loja 4, que faturava menos dentre todas, tem uma boa média.

![media_avaliacao_loja](https://github.com/user-attachments/assets/efb2c08a-86da-49dc-a385-75be03aea432)

### Frete Médio por Loja
Quem gosta de pagar frete em suas compras? Da mesma forma, valres altos de frete podem significar baixa retenção de clientes ou menor satisfação, pois o custo final seria maior para quem escolhe comprar na loja. Assim, novamente vemos a Loja 1 liderar com a maior média de frete da rede, sendo a Loja 4 a com menor média. Isto é um forte indicador de que a Loja 1 é um ponto de venda deprodutos grandes e mais difíceis de transportar, ou que a maioria dos clientes desta loja moram a maiores distâncias. O oposto poderia ser dito quanto à Loja 4.

![frete_medio_loja](https://github.com/user-attachments/assets/df89e280-2d27-4d18-b4b9-b677403ab782)

### Pontuação por Loja
Você talvez encontre algumas viaráveis para pontuação no código. Elas armazenaram os valores de pontuação de cada loja, que no final serviram para definir qual teve a pior performance. Quanto maior a pontuação, menos indicada seria a loja para venda.

![Pontuação por Loja](https://github.com/user-attachments/assets/f6d8baf0-fdaf-4fa7-9cbd-bac7fa22b214)

## Como Acessar o projeto

### 1. Dowload do Arquivo 
Baixe o arquivo no GitHub em formato Zip e salve-o em um diretório de sua preferência.

![Passo 1](/passo_1.jpg)

### 2. Upload para Google Drive.
Acesse seu Google Drive e faça o Upload do arquivo .iypnb para o diretório de sua preferência.

![Passo 2A](/passo_2a.jpg)
![Passo 2B](/passo_2b.jpg)
![Passo 2C](/passo_2c.jpg)

### 3. Abrindo o Arquivo
Abra o arquivo em seu Drive. Ao carregar, selecione Runtime e Run All, ou utilize o atalho Ctrl + F9 para agilizar. Pronto! Basta analisar os resultados.

![Passo 3](/passo_3.jpg)









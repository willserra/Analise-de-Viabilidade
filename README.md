# 🎯 **Desafio Alura Store – Análise de Viabilidade em Python com Pandas e Matplotlib**
🎯 Propósito da Análise Realizada
O objetivo principal desta análise é fornecer ao proprietário das lojas, o Sr. João , uma visão detalhada e baseada em dados sobre o desempenho de suas quatro lojas. A partir dessa análise, ele poderá tomar uma decisão estratégica informada sobre qual loja deve ser vendida para maximizar a eficiência operacional e o retorno sobre o investimento.

🔍 Contexto do Projeto
O projeto faz parte do Desafio Alura Store , que simula a rotina de um Cientista de Dados aplicando conceitos práticos de manipulação de dados, geração de insights visuais e tomada de decisões baseadas em métricas. O desafio foi desenvolvido no âmbito do programa Oracle Next Education (ONE) , permitindo a aplicação prática de ferramentas como Python , Pandas e Matplotlib .

📊 Objetivos Específicos

Avaliar o Faturamento Total por Loja

Identificar qual loja apresenta o maior e o menor faturamento.

Analisar a distribuição de receitas entre as unidades.

Analisar as Categorias Mais Vendidas

Descobrir quais categorias de produtos são mais populares em cada loja.

Identificar padrões de consumo e preferências regionais.

Medir a Satisfação dos Clientes

Comparar a média de avaliações dos clientes entre as lojas.

Identificar oportunidades para melhorar a experiência do cliente nas lojas com avaliações mais baixas.

Identificar Produtos Mais e Menos Vendidos

Destacar os produtos com melhor e pior desempenho em vendas.

Avaliar possíveis causas para baixas vendas de determinados produtos.

Analisar o Custo Médio de Frete por Loja

Comparar o custo logístico entre as lojas.

Verificar se o frete impacta negativamente na competitividade de alguma unidade.

Gerar Recomendações Baseadas em Dados

Consolidar todos os insights obtidos para sugerir qual loja deve ser vendida.

Apoiar o Sr. João na tomada de decisão estratégica.


🧠 Importância da Análise
Esta análise não apenas fornece uma visão clara do desempenho atual das lojas, mas também permite identificar áreas de melhoria e oportunidades de crescimento. Ao utilizar métricas como faturamento , avaliações dos clientes , produtos mais vendidos e custo de frete , a análise garante que a decisão final seja embasada em dados concretos e objetivos.

📈 Resultados Esperados
Com base nos insights gerados, espera-se que o Sr. João consiga:

Maximizar a Eficiência Operacional : Concentrar recursos nas lojas com maior potencial de crescimento.
Melhorar a Rentabilidade : Reduzir custos e aumentar o retorno sobre o investimento.
Tomar Decisões Estratégicas : Utilizar os dados para fundamentar escolhas de longo prazo.

✨ Conclusão
A análise realizada visa transformar dados brutos em insights acionáveis, permitindo que o Sr. João tome uma decisão estratégica informada e alinhada aos seus objetivos de negócio. Este projeto demonstra o poder da análise de dados como ferramenta essencial para a tomada de decisões no mundo corporativo.

📂 Estrutura do Projeto e Organização dos Arquivos

O projeto foi organizado de forma clara e eficiente para facilitar a navegação, execução e manutenção. Abaixo, detalhamos como os arquivos e pastas estão estruturados, garantindo que todas as etapas da análise estejam bem documentadas e acessíveis.

📋 Descrição das Pastas e Arquivos
1. Pasta dados/
   
Contém os arquivos CSV com os dados brutos utilizados na análise.
Cada arquivo representa uma loja específica:
loja_1.csv: Dados da Loja 1.
loja_2.csv: Dados da Loja 2.
loja_3.csv: Dados da Loja 3.
loja_4.csv: Dados da Loja 4.

Esses arquivos são a base para todas as análises realizadas no projeto.

🔧 Fluxo de Trabalho

Coleta de Dados
Os dados brutos foram obtidos diretamente do GitHub da Alura e armazenados na pasta dados/.


Análise Exploratória
O notebook (analise_alura_store.ipynb) foi utilizado para realizar a análise exploratória dos dados, incluindo cálculos de métricas e geração de gráficos.


Visualizações
Os gráficos gerados foram salvos na pasta graficos/ para facilitar a apresentação dos resultados.

Documentação
Todo o processo foi documentado no arquivo README.md, garantindo transparência e facilidade de uso.

🛠️ Ferramentas Utilizadas

Python : Linguagem principal para manipulação e análise de dados.

Pandas : Biblioteca usada para tratamento e análise de dados tabulares.

Matplotlib : Ferramenta para geração de gráficos estáticos.

Jupyter Notebook : Ambiente interativo para desenvolvimento do projeto.


📊 Exemplos de Gráficos e Insights Obtidos

A análise realizada no projeto Desafio Alura Store gerou diversos gráficos e insights que ajudaram a entender o desempenho das lojas. Abaixo, destacamos alguns exemplos dos gráficos mais relevantes e os principais insights extraídos de cada um.

1. Faturamento Total por Loja
   
 Gráfico
 
![image](https://github.com/user-attachments/assets/08398192-9c01-43fb-9244-f2e877817f04)


Descrição : Este gráfico de setores mostra o faturamento total de cada loja.
Dados Representados :
Loja 1 : R$ 1.534.509,12

Loja 2 : R$ 1.488.459,06

Loja 3 : R$ 1.488.459,06

Loja 4 : R$ 1.384.497,58

💡 Insights
A Loja 1 lidera em faturamento, indicando maior lucratividade.

A Loja 4 apresenta o menor faturamento, sugerindo menor eficiência comercial.

Essa diferença evidencia que a Loja 4 pode ser a candidata ideal para venda.

2. Vendas por Categoria
   
📈 Gráfico

![image](https://github.com/user-attachments/assets/85612e8b-b850-4443-914f-c223bba05c26)


Descrição : Este gráfico de linhas compara as vendas por categoria entre as lojas.

Categorias Mais Populares :

Eletrônicos : Lideram nas Lojas 1 e 2 .

Móveis : Mais vendidos na Loja 3 .
Livros : Destaque na Loja 2 .

💡 Insights

As categorias mais populares variam significativamente entre as lojas, refletindo diferentes estratégias de mercado.

A Loja 4 apresenta distribuição equilibrada, mas sem destaque em nenhuma categoria específica.


3. Média de Avaliação dos Clientes

📈 Gráfico

![image](https://github.com/user-attachments/assets/430c965f-ce90-4d8f-9711-0d1311d1996e)




Descrição : Este gráfico mostra a média de avaliações dos clientes por loja.
Médias de Avaliação :
Loja 1 : 3.98

Loja 2 : 4.04

Loja 3 : 4.05

Loja 4 : 4.00

💡 Insights

A Loja 3 tem a maior média de avaliação, indicando maior satisfação geral.

A Loja 4 , apesar de ter uma média razoável, apresenta menor proporção de clientes satisfeitos em relação às outras lojas.


4. Produtos Mais Vendidos
   
📈 Gráfico

![image](https://github.com/user-attachments/assets/97b46c98-1ed7-48ee-8e71-0eaf92e54ebe)


Descrição : Este gráfico de barras agrupadas exibe os produtos mais vendidos em cada loja.
Exemplos de Produtos Mais Vendidos :

Loja 1 : Micro-ondas, TVs LED UHD 4K, Secadoras de Roupas.

Loja 2 : Livros ("Iniciando em Programação"), Bateria, Violão.

Loja 3 : Mesa de Jantar, Cama King.

💡 Insights

A Loja 1 se destaca com produtos premium, como eletrônicos e eletrodomésticos.

A Loja 4 não apresenta produtos com grande destaque, indicando falta de atratividade.

5. Frete Médio por Loja

![image](https://github.com/user-attachments/assets/94a76c49-0ba1-4281-98bc-74032c60ecdd)

   
📈 Gráfico


Descrição : Este gráfico de linha compara o custo médio de frete por loja.
Custos Médios de Frete :

Loja 1 : R$ 34.69

Loja 2 : R$ 33.62

Loja 3 : R$ 33.07

Loja 4 : R$ 33.62

💡 Insights
A Loja 3 tem o menor custo médio de frete, indicando vantagem logística.
Apesar do custo intermediário, a Loja 4 não compensa com retorno financeiro adequado.

6. Proporção de Satisfeitos vs. Insatisfeitos

📈 Gráfico

![image](https://github.com/user-attachments/assets/75d62b2b-2ba2-4c16-ac30-d4c057d3e31a)


Descrição : Este gráfico de barras empilhadas mostra a proporção de clientes satisfeitos e insatisfeitos por loja.
Proporções :

Loja 1 : 4.29 (Satisfeitos/Insatisfeitos)

Loja 2 : 4.87

Loja 3 : 4.37

Loja 4 : 4.44

💡 Insights
A Loja 2 apresenta a melhor proporção de satisfeitos vs. insatisfeitos.

A Loja 4 tem uma proporção alta, mas seu volume total de avaliações é menor, indicando menor engajamento.

✨ Conclusão
Os gráficos e insights obtidos fornecem uma visão abrangente do desempenho das lojas, permitindo identificar pontos fortes e fracos em cada unidade. Com base nessas análises, fica claro que a Loja 4 apresenta o pior desempenho geral em termos de faturamento, avaliações e distribuição de vendas, tornando-a a principal candidata para venda.

Esses insights são essenciais para orientar decisões estratégicas e maximizar o retorno sobre o investimento do Sr. João.


🚀 Instruções para Executar o Notebook

Este guia fornece um passo a passo detalhado para executar o notebook desenvolvido no projeto Desafio Alura Store . Siga as etapas abaixo para garantir que tudo funcione corretamente.

📂 Pré-requisitos

Antes de executar o notebook, certifique-se de que você tenha os seguintes itens configurados no seu ambiente:

Python 3.x instalado:

Verifique a instalação executando o comando:

bash

Copiar

1

python --version

Caso não esteja instalado, baixe-o em: python.org .

Bibliotecas necessárias :

As bibliotecas utilizadas no projeto são:

pandas
matplotlib
numpy

Instale-as usando o seguinte comando:

bash
Copiar
1
pip install pandas matplotlib numpy

Ambiente de execução :

Recomendamos o uso do Google Colab para rodar o código.

Para usar o Google Colab, acesse: colab.research.google.com .

Arquivos de dados :
Certifique-se de ter os arquivos CSV das lojas (loja_1.csv, loja_2.csv, etc.) disponíveis no mesmo diretório do notebook ou carregue-os via URL.

▶️ Passos para Executar o Notebook

Siga os passos abaixo para executar o notebook com sucesso:

1. Clonar ou Baixar o Projeto
   
Clone o repositório do GitHub ou faça o download dos arquivos manualmente:

bash

Copiar

1
git clone https://github.com/seu-usuario/nome-do-repositorio.git


Alternativamente, baixe os arquivos como ZIP e extraia-os no seu computador.

4. Abrir o Notebook

Abra o arquivo .ipynb no Jupyter Notebook ou faça upload do arquivo no Google Colab .

5. Instalar Dependências
Execute a célula de instalação de dependências no início do notebook para garantir que todas as bibliotecas estejam instaladas:

python

Copiar

1

!pip install pandas matplotlib numpy

6. Carregar os Dados
   
Certifique-se de que os arquivos CSV estão acessíveis. Se estiver usando URLs, verifique se os links estão atualizados e funcionais.

Exemplo de carregamento de dados:

python

Copiar

import pandas as pd

loja1 = pd.read_csv('loja_1.csv')

loja2 = pd.read_csv('loja_2.csv')

7. Executar as Células

Execute as células do notebook sequencialmente, começando pelas configurações iniciais até as análises e gráficos.

Use o botão "Run" no Google Colab ou pressione Shift + Enter para executar cada célula.

8. Verificar os Resultados

Após a execução, os resultados das análises e os gráficos gerados serão exibidos diretamente no notebook.

Certifique-se de que todos os gráficos e tabelas foram renderizados corretamente.

🛠️ Dicas Adicionais

Erros comuns :
Se ocorrer um erro relacionado a bibliotecas ausentes, execute novamente o comando de instalação (pip install).

Certifique-se de que os nomes dos arquivos CSV correspondam aos usados no código.

Otimização :
Para melhor desempenho, use o Google Colab com GPU ativada (se disponível) para processamento mais rápido.

Salvar resultados :
Exporte os gráficos gerados como imagens ou salve o notebook completo após a execução:

python

Copiar

from IPython.display import Image
plt.savefig('grafico.png')

📢 Suporte
Caso encontre dificuldades ou tenha dúvidas durante a execução do notebook, consulte a documentação oficial das bibliotecas utilizadas ou entre em contato com o autor do projeto:

Autor : William S. Serra
Repositório :(https://github.com/willserra/Analise-de-Viabilidade)

✨ Agora você está preparado para executar o notebook e explorar as análises realizadas no projeto. Boa sorte! ✨

📊 DASHBOARD DE VENDAS 
✅ 1. Base de Dados Utilizada
A base utilizada contém dados fictícios de vendas, simulando um cenário real de uma empresa com múltiplos vendedores, produtos e localidades. A tabela está localizada na aba "Base de Dados" e contém os seguintes campos:

Coluna	Descrição
Data da Venda	Data em que a venda foi realizada (formato AAAA-MM-DD)
Produto	Nome do produto vendido (ex: Notebook, Celular, Monitor, etc.)
Vendedor	Nome do vendedor responsável pela venda
Cidade	Cidade onde a venda foi registrada
Quantidade	Quantidade de unidades vendidas
Preço Unitário (R$)	Valor unitário do produto em reais
Valor Total (R$)	Valor total da venda (Quantidade × Preço Unitário)
Ano e Mês	Colunas auxiliares derivadas da data para análises por período
Essa base contém 2.000 registros simulados, cobrindo o ano de 2024.

🧩 2. O Que o Dashboard Mostra (Aba "Dashboard")
▶️ Gráfico de Vendas por Vendedor
Mostra o total vendido por cada vendedor, em forma de gráfico de colunas.

Inclui rótulos de dados com os valores em reais (R$).

Ordenado do maior para o menor valor total vendido.

▶️ Gráfico de Vendas por Mês
Mostra o total vendido por mês, em forma de gráfico de colunas.

Inclui rótulos de dados com os valores em reais (R$).

Ordenado por mês.


🛠️ 3. Como Reproduzir Esse Dashboard no Excel
Se quiser criar algo semelhante diretamente no Excel, siga os passos:

🔹 Etapa 1: Organize a base de dados
Insira seus dados com colunas semelhantes às citadas acima.

Certifique-se de formatar a coluna de datas corretamente.

Crie colunas auxiliares para "Mês" e "Ano", se quiser filtros por período.

🔹 Etapa 2: Crie Tabela Dinâmica
Selecione a base inteira.

Vá até a aba Inserir > Tabela Dinâmica.

Escolha "Nova planilha" e insira os campos:

Linhas: Vendedor

Valores: Valor Total (R$) (como Soma)

🔹 Etapa 3: Crie um gráfico
Com a tabela dinâmica selecionada, vá até Inserir > Gráfico de Colunas.

Personalize com cores, rótulos e título.

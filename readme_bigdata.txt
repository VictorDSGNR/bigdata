Trabalho realizado por Victor de Almeida Costa

📊 Projeto: Análise de Dados com Pandas
Este projeto tem como objetivo aplicar técnicas de limpeza, transformação e visualização de dados utilizando a biblioteca Pandas em Python. Os dados utilizados representam sessões de exercícios físicos, contendo informações como duração, frequência cardíaca e calorias gastas.

🧠 Etapas do processamento
- Importação de bibliotecas
- Instalação e uso do pandas.
- Leitura dos dados
- Os dados foram carregados a partir de uma string formatada como CSV e salvos no arquivo dados.csv.
- Visualização inicial
- Foram exibidas as primeiras e últimas linhas do conjunto de dados para inspeção.
- Criação de cópia
- Criada a variável df_nova como cópia do DataFrame original para preservar os dados brutos.
- Tratamento de valores nulos
- Substituição de "NaN" na coluna Calories por 0.
- Substituição de "NaN" na coluna Date por "1900/01/01".
- Conversão de datas
- Remoção de aspas simples e espaços.
- Correção do valor "20201226" para o formato "2020/12/26".
- Conversão da coluna Date para o tipo datetime, com tratamento de erros.
- Remoção de registros inválidos
- Exclusão de linhas onde a data não pôde ser convertida (valores nulos ou mal formatados).

📁 Estrutura dos dados
|  |  | 
| ID |  | 
| Duration |  | 
| Date |  | 
| Pulse |  | 
| Maxpulse |  | 
| Calories |  | 



🚀 Como executar
- Instale as dependências:
pip install pandas
- Execute o notebook big_data.ipynb no VS Code ou Jupyter Notebook.

📌 Observações
- O projeto foca em manipulação de dados tabulares com Pandas.
- Ideal para iniciantes em ciência de dados que desejam praticar limpeza e transformação de dados.

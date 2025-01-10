# Taxa-CDI-Python

Neste projeto foi desenvolvido um script automatizado para a coleta, processamento e visualização da taxa CDI utilizando Python com os pacotes Requests, Pandas e Seaborn. A finalidade é capturar dados em tempo real do Banco Central do Brasil e gerar gráficos de tendência.


●	Captura de Dados: Através do pacote Requests foi realizada as requisições HTTP da API do banco central, capturando os dados da taxa CDI.

●	Tratamento dos Dados: Realizado a manipulação dos dados JSON da API, utilizando os pacotes ‘json’ e ‘pandas’, salvando as informações em um DataFrame para facilitar a análise.

●	Armazenamento: Através do módulo ‘csv’ armazenei os dados no formato CSV.

●	Visualização: Com o módulo ‘seaborn’ gerei gráficos de linha (line plot) para apresentar a variação da taxa CDI, melhorando a visualização e a compreensão dos dados ali apresentados.


# Processos_SQL_SFT

Este processo envolve consulta SQL utilizando Python para realizar envios diários para uma pasta SFTP. 
A intenção é rotacionar conforme a necessidade diária, salvando os arquivos enviado os em pastas temporárias. 
A cada novo envio, verifica-se se existe um arquivo correspondente do mesmo segmento/empresa. 
Se existir, o arquivo é substituído se for da mesma empresa e o mesmo arquivo, com o objetivo de backups ao menos por 24 horas. 
Após essa operação, os arquivos são salvos na pasta SFTP de terceiros.


# Query_SQL_Python
O objetivo deste projeto é facilitar a extração de dados por meio de consultas SQL utilizando Python, 
oferecendo uma solução configurável e simplificada.
Com essa abordagem, é possível executar consultas e carregar os resultados em estruturas de dados como DataFrames, 
facilitando a análise dos dados com as principais variáveis já disponíveis, fazer todas as alterações necessárias e após os processos a exportação das informações.

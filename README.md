# Processos_SQL_SFT

Este processo envolve consulta SQL utilizando Python para realizar envios diários para uma pasta SFTP. 
A intenção é rotacionar conforme a necessidade diária, salvando os arquivos enviados em pastas temporárias. 
A cada novo envio, verifica-se se existe um arquivo correspondente do mesmo segmento/empresa. 
Se existir, o arquivo é substituído se for da mesma empresa e o mesmo arquivo, com o objetivo de backups ao menos por 24 horas. 
Após essa operação, os arquivos são salvos na pasta SFTP de terceiros.


# Query_SQL_Python

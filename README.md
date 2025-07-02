# Projeto de análise de dados Telecom X

Nesse projeto, foram liberados diversos dados de uma empresa de serviços de internet e streaming na qual foi posta em prática as técnicas de ETL (Extract, Transform, Load) por meio da linguagem de programação Python e suas bibliotecas (Pandas, Matplotlib e Seaborn).

Primeiro **importei os dados** que estavam hospedados em uma URL em **formato JSON**. Os dados estavam separados em muitos *DataFrames* desnecessários e prejudiciais para análises, com isso eu **fiz a junção desses dados em apenas um *Dataframe* geral**, **limpei os dados**, **criei novas colunas** necessárias para as equipes de cientistas de dados e mudei a tipologia de algumas colunas para uma melhor análise e depois **salvei o novo *DataFrame*** já limpo e organizado no Arquivo **“TelecomX_Data.json”**. O processo completo de limpeza de dados está presente no arquivo **“TratandoDados.ipynb”**.

Foram feitas diversas análises utilizando a biblioteca **Pandas (análise), Matplotlib e Seaborn (gráficos)** que estão presentes no arquivo “**Challenge.ipynb”** e de maneira visual no relatório **"Relatorio.ipynb”.**

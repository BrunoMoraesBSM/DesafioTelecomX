# Projeto de análise de dados Telecom X

Nesse projeto, foram liberados diversos dados de uma empresa de serviços de internet e streaming na qual foi posta em prática as técnicas de ETL (Extract, Transform, Load) por meio da linguagem de programação Python e suas bibliotecas (Pandas, Matplotlib e Seaborn).

Primeiro **importei os dados** que estavam hospedados em uma URL em **formato JSON**. Os dados estavam separados em muitos *DataFrames* desnecessários e prejudiciais para análises, com isso eu **fiz a junção desses dados em apenas um *Dataframe* geral**, **limpei os dados**, **criei novas colunas** necessárias para as equipes de cientistas de dados e mudei a tipologia de algumas colunas para uma melhor análise e depois **salvei o novo *DataFrame*** já limpo e organizado no Arquivo **“TelecomX_Data.json”**. O processo completo de limpeza de dados está presente no arquivo **“TratandoDados.ipynb”**.

Foram feitas diversas análises utilizando a biblioteca **Pandas (análise), Matplotlib e Seaborn (gráficos)** que estão presentes no arquivo “**Challenge.ipynb”** e de maneira visual no relatório **"Relatorio.ipynb”.**

# Relatório

Essa análise de dados foi feita para melhorar a estrutura dos dados da empresa e encontrar informações que possam ser uteis para a melhoria da empresa. Uma das informações mais importantes retiradas dessa análise foi a quantidade demasiada alta de evasão de cliente.

Foi feita uma reestruturação de algumas colunas da tabela e criação de outras. Além disso, todas as tabelas foram unidas em apenas uma tabela geral.

Na análise de evasão notou-se que cerca de 26% dos planos foram cancelados, não havendo grande relevancia entre gênero.

![output](https://github.com/user-attachments/assets/e8c8302e-dcc6-4b54-904a-3235dc557240) ![output](https://github.com/user-attachments/assets/ab4c1bfb-9679-45c7-940d-9d33dfdfa641)

No entanto, notou-se uma grande quantidade de evasão dos clientes senior, onde mesmo sendo uma parcela muito menor no número total de evasão, pode ser um ponto de atenção.
![output](https://github.com/user-attachments/assets/169683ef-a27d-4e22-a8f8-b5e50d0f1d67)
![output](https://github.com/user-attachments/assets/65ae3b5b-2137-4187-b66b-1b8c3021101a)

Notou-se também que quanto maior o gasto mensal, maior é a porcentagem de evasão, sendo que a menor porcentagem é de 20% onde o gasto máximo é de R$ 45,00.
![output](https://github.com/user-attachments/assets/f2b07aef-e0e0-43d1-b252-0202ad5705b7)
![output](https://github.com/user-attachments/assets/c903960c-cbae-4d91-9e53-5f2caea82b0f)

A quantidade de meses e o tipo de contrato também influeciam a taxa de permanencia, sendo que quanto mais tempo o cliente está assinando, menos chance ele tem de cancelar os serviços.

![output](https://github.com/user-attachments/assets/63f62aa7-e470-42f1-a4f8-04335f9ce619)

Outra análise útil é a porcentagem de cancelamento por tipo de contrato, onde os contratos de maior duração tendem a ter menos cancelamentos e também a média de meses que as contas permanecem ativas aumenta conforme a duração de cada contrato

![output](https://github.com/user-attachments/assets/dae5f4a6-8aae-4082-b23c-ebf0ee154b32)
![output](https://github.com/user-attachments/assets/03d2d89a-9c9e-477b-abd3-1f979aaeee55)

## Conclusões

A análise evidenciou uma taxa de evasão de 26%, sendo influenciada principalmente pelo perfil do cliente (idoso ou não), valor gasto mensalmente, tempo de permanência na empresa e tipo de contrato.

Clientes idosos apresentam maior tendência de cancelamento, mesmo representando uma menor fatia da base total. Clientes que gastam mais também tendem a cancelar mais, o que pode indicar problemas de percepção de valor. Além disso, foi identificado que clientes com menor tempo de conta e contratos mensais são os que mais cancelam os serviços, enquanto aqueles com contratos mais longos e maior tempo de relacionamento demonstram maior fidelização.

Possíveis soluções para os problemas citados são:

* Oferecer incentivos para contratos mais longos, como descontos progressivos.
* Criar programas de fidelidade e benefícios para clientes seniores.
* Avaliar a percepção de custo-benefício dos planos com gasto mensal elevado.
* Implementar ações de retenção nos primeiros 2 anos de conta, período mais crítico.
* Monitorar feedbacks de clientes que cancelam, especialmente entre os que têm contratos curtos.

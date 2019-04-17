# Bot de exemplo para o DialogFlow


## Informações

Aqui apenas constam os dados referentes ao Fullfilment baseado na conversação de exemplo do dialogflow, informações sobre os agente utilizados serão acrescentadas em futuras versões.
O exemplo simula uma universidade onde os alunos fazem diversos tipos de pesquisas cadastram seus dados no processo seletivo, os mesmos podem consulstar seus dados, cancelando a sua inscrição no processo seletivo e além disso podem alterar dados, alémd e fazer suas consultas e agendamentos na faculdade.

É feita uma validação com o Joi para todas as operações de request na base de dados e para ações de inclusão e alteração(que levam CEP) é utlizada a ferramenta buscaCep que valida do CEP digitado.

O exemplo é mais lúdico e possui trataivas rudimentares para o CPF e não trata CEP.

Em futuras versões, será feito um tratamento com promisses para lidar com as ações assíncronas em banco de dados.

# Esquema-Conceitual-Oficina-Mecanica
 Construindo um Esquema Conceitual para Banco De dados de umaOficina Mecanica

Objetivo:
Cria o esquema conceitual para o contexto de oficina com base na narrativa fornecida

Narrativa:
- Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
(daserviço) 

- Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas
(cliente) 

- Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
(veiculo)

- A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra 
(mão de obra)

- O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços 
(peças)

- A mesma equipe avalia e executa os serviços
(equipe)

- Os mecânicos possuem código, nome, endereço e especialidade
(mecanicos)

	Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.
(ordem de serviço)

# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS


Data: [28 de agosto de 2025]

Empresa: Abstergo Industries

Responsavel: [Victor Augusto Rech]


## INTRODUÇÃO

Este relatório apresenta o processo de implementação de ferramentas da Amazon Web Services (AWS) na Abstergo Industries. A iniciativa visa modernizar a infraestrutura de TI da empresa, que atualmente não utiliza serviços de nuvem, com foco principal na diminuição imediata de custos. Foram selecionados três serviços AWS estratégicos para atingir este objetivo, demonstrando os benefícios financeiros e operacionais da computação em nuvem.

## Descrição do Projeto

O projeto de implementação foi dividido em três etapas, cada uma focada em um serviço AWS específico para endereçar um desafio de custo diferente dentro da empresa.

Etapa 1:Implementação do Amazon S3

- [Amazon Simple Storage Service (S3)]

- [Redução de custos de armazenamento de dados]

- [A Abstergo Industries possui uma grande quantidade de dados de pesquisa e desenvolvimento, relatórios de testes clínicos e documentos de regulamentação armazenados em servidores físicos. A manutenção desses servidores é cara e a capacidade de armazenamento é limitada. Com o S3, migramos esses dados para a nuvem, eliminando a necessidade de comprar e manter hardware de armazenamento. A empresa agora paga apenas pelo espaço de armazenamento que realmente usa e se beneficia de custos mais baixos por gigabyte, alta durabilidade e backups automáticos]


Etapa 2:Implementação do Amazon EC2

- [Implementação do Amazon EC2 Spot Instances]

- [Redução de custos de computação para cargas de trabalho flexíveis]

- [O setor de P&D da Abstergo utiliza servidores para simulações e análise de dados que não precisam ser executadas 24/7 e podem tolerar interrupções. Em vez de usar instâncias EC2 sob demanda, que são mais caras, implementamos o uso de Spot Instances. Essas instâncias aproveitam a capacidade não utilizada da AWS e oferecem descontos de até 90%. Isso permite que a equipe de pesquisa execute tarefas intensivas em computação por uma fração do custo, acelerando o ciclo de inovação sem estourar o orçamento]


Etapa 3:Implementação do Amazon RDS

- [Implementação do Amazon RDS]

- [ Redução de custos de manutenção de banco de dados]

- [A Abstergo mantém vários bancos de dados para gerenciar informações de pacientes, inventário de medicamentos e dados financeiros. A administração desses bancos de dados em servidores on-premise exige horas de trabalho de engenheiros para tarefas como backups, aplicação de patches de segurança e atualizações. Com o Amazon RDS, a Abstergo migrou seus bancos de dados para a nuvem, delegando essas tarefas de manutenção para a AWS. Isso reduz a carga de trabalho da equipe de TI, permitindo que eles se concentrem em projetos mais estratégicos, e elimina os custos de licenciamento e hardware associados à gestão de bancos de dados locais]




## Conclusão

A implementação de ferramentas AWS na Abstergo Industries tem como esperado uma significativa redução de custos operacionais e de capital (CapEx), eliminando gastos com aquisição e manutenção de hardware, além de otimizar o uso dos recursos de computação e armazenamento. A empresa se beneficia de maior agilidade, escalabilidade e resiliência, preparando o terreno para uma transformação digital completa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.


## Anexos


- Plano de Migração de Dados para S3

- Relatório de Economia com EC2 Spot Instances

- Manual de Operação do Amazon RDS

Assinatura do Responsável pelo Projeto: Victor Rech


[Victor Augusto Rech] 
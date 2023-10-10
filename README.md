## Processo Seletivo - Controle de Fluxo e Repetições

Neste projeto, desenvolvi um sistema simples para gerenciar um processo seletivo, aplicando conceitos de controle de fluxo, repetições e exceções. Abordo os seguintes aspectos:

### Avaliação das Propostas dos Candidatos

No primeiro aspecto, avalio as propostas salariais dos candidatos em relação ao salário base de R$ 2.000,00. Sigo as seguintes regras:

- Se o valor salário base for **maior** que o valor salário pretendido pelo candidato, imprimo "LIGAR PARA O CANDIDATO."
- Se o valor salário base for **igual** ao valor salário pretendido pelo candidato, imprimo "LIGAR PARA O CANDIDATO, COM CONTRA PROPOSTA."
- Se nenhuma das condições acima for atendida, imprimo "AGUARDO RESULTADO DOS DEMAIS CANDIDATOS."

### Seleção de Candidatos para Entrevista

No segundo aspecto, limito o número de candidatos para entrevista a um máximo de 5. Os candidatos selecionados são aqueles cujo salário pretendido seja menor ou igual ao salário base de R$ 2.000,00. 

### Impressão da Lista de Candidatos Selecionados

Após a seleção dos candidatos, imprimo a lista dos candidatos selecionados. Esta lista será disponibilizada ao departamento de Recursos Humanos para futuros contatos.

### Tentativas de Contato com os Candidatos Selecionados

No quarto aspecto, trato das tentativas de contato com os candidatos selecionados. O RH tem um limite de 3 tentativas para cada candidato. Faço a seguinte análise:

- Se o candidato atender o telefone, imprimo "CONSEGUI CONTATO COM [CANDIDATO] APÓS [TENTATIVA] TENTATIVA(S)."
- Se o candidato não atender após as 5 tentativas, imprimo "NÃO CONSEGUI CONTATO COM O [CANDIDATO]."

Com esses aspectos, construí um sistema simples para gerenciar um processo seletivo, que pode ser útil em cenários de contratação de pessoal.

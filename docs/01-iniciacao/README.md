# Iniciação

> A fase de iniciação, em gerência de projetos, é o estágio que estabelece as bases para o sucesso do empreendimento. 
> Durante essa etapa, os objetivos definidos, identificando-se suas metas, escopo, partes interessadas (*stakeholders*) e restrições. 
> É o momento em que a viabilidade do projeto é avaliada, analisando-se recursos necessários, riscos potenciais e benefícios esperados.
> Nesta etapa é elaborado o Termo de Abertura do Projeto (TAP).
> Essa fase serve como um alicerce estratégico, proporcionando uma compreensão abrangente do que o projeto busca alcançar e delineando as diretrizes que orientarão as etapas subsequentes. 
> O sucesso na fase de iniciação contribui significativamente para a eficácia do gerenciamento de projetos como um todo.

# Estrutura do Documento

- [Fase de Iniciação](#iniciação)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Critérios de Sucessos](#critérios-de-sucesso)
- [Partes Interessadas](#partes-interessadas)
  - [Identificação das Partes Interessadas](#identificação-das-partes-interessadas)
  - [Avaliação das Partes Interessadas](#avaliação-das-partes-interessadas)
- [Termo de Abertura do Projeto](#termo-de-abertura-do-projeto)
  - [Estimativa de Custo](#estimativa-de-custo)
  - [Estimativa de Prazo](#estimativa-de-prazo)
  - [Escopo Preliminar e Premissas](#escopo-preliminar-e-premissas)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos Não Funcionais](#requisitos-não-funcionais)
    - [Restrições](#restrições)
    - [Contra-Escopo](#contra-escopo)
    - [Condições para início do Projeto](#condições-para-início-do-projeto)
  - [Marcos Agendados e Entregas](#marcos-agendados-e-entregas)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)

# Introdução
Utilizar reconhecimento facial e análise de dados comportamentais para identificar criminosos e assaltos em andamento. O objetivo do projeto é uma plataforma que possa ser utilizada por forças de segurança para melhorar a segurança pública.

Possíveis funcionalidades e  recursos: Reconhecimento facial, Análise de Dados Comportamentais, Banco de dados de criminosos, Alertas e Notificações, Relatórios e análises, Identificação de pessoas desaparecidas(possibilidade tendo em vista a aplicação de reconhecimento facial)

## Problema

O principal problema que este projeto visa resolver é a ineficiência na detecção e resposta a crimes em tempo real, a identificação tardia de criminosos, e a dificuldade em gerir e utilizar de forma eficaz os dados relacionados à segurança pública. 

## Objetivos

Objetivo Geral:
Desenvolver uma plataforma integrada de reconhecimento facial e análise comportamental que permita às forças de segurança identificar e responder rapidamente a crimes em andamento, melhorar a gestão de dados criminais e auxiliar na localização de pessoas desaparecidas.

Objetivos Específicos:

1. Implementar um sistema de reconhecimento facial capaz de identificar criminosos conhecidos e pessoas desaparecidas em tempo real, utilizando câmeras de vigilância existentes.
2. Desenvolver um módulo de análise comportamental que detecte atividades suspeitas e alerte as forças de segurança antes que crimes sejam cometidos.
3. Integrar um sistema de alertas e notificações em tempo real, permitindo uma comunicação rápida e eficaz entre as forças de segurança e outros stakeholders.

## Justificativa

A construção desta plataforma é justificada pela necessidade crescente de ferramentas tecnológicas que possam melhorar a eficiência e a eficácia das operações de segurança pública. Com a criminalidade em alta, as forças de segurança necessitam de soluções que possam fornecer informações precisas e em tempo real, permitindo a identificação e a resposta imediata a crimes e atividades suspeitas.

Além disso, a integração de tecnologias como o reconhecimento facial e a análise comportamental pode otimizar a utilização dos recursos de segurança, reduzindo o tempo e os custos envolvidos na identificação de criminosos e na resolução de crimes. A plataforma também terá um impacto significativo na localização de pessoas desaparecidas, um problema crítico que afeta muitas famílias e comunidades.

## Critérios de Sucesso


# Partes Interessadas

> Relacione as partes interessadas no seu projeto. 
> Você deve descrever as partes interessadas e indicar qual o nível de influência em relação ao projeto.
> Indique as principais pessoas (clientes, fornecedores, etc), indicando possíveis expectativas, nível de influência e possível importância para o sucesso do projeto.

> Você pode utilizar como referência o seguinte documento:
> [Registro de Partes Interessadas](artefatos/registro-partes-interessadas.xlsx)

## Identificação das Partes Interessadas

| Nome            | Posição / Cargo | Papel Projeto | E-mail      | Telefone    |
|-----------------|-----------------|---------------|-------------|-------------|
|Rogério Greco    |Secretário de Segurança Pública de Minas Gerais |Cliente |rg@gmail.com|(31)91111-1111|
|Lucas Meira Duque|Gerente de T.I.|Testes e depuração, liderança de projeto, gestão de riscos e segurança e gerenciamento de stakeholders|lmd@gmail.com|(31)92222-2222|
|João Gabriel Mendonça|Analista de Sistemas do cliente|Coleta e análise de requisitos, prototipagem e validação, consultoria técnica, feedback e melhorias|jg@gmail.com|(31)93333-3333|
|Nathália de Carvalho|Desenvolvedor|Desenvolvimento e implemetação de segurança do software|ndc@gmail.com|(31)94444-4444|
|Luís Campelo     |Desenvolvedor|Integração com o banco de dados, desenvolvimento de API's|lc@gmail.com|(31)95555-5555|

> Opções de identificação dos stakeholders:
> - Nome: nome da parte interessada (inclui funcionários da empresa e do cliente)
> - Posição / Cargo: Identificação do cargo da parte interessada
> - - Ex.: Gerente de TI, Funcionário da Linha de Produção, Presidente, Analista de Sistema do Cliente, Desenvolvedor, etc.
> - Papel no Projeto: Papel da pessoa no projeto
> - - Ex.: Desenvolvedor, Analista de Requisitos, Analista de Testes, Product Owner, etc.
> - E-mail: E-mail do Stakeholder (*não utilizar informações pessoais*)
> - Telefone: Telefone do Stakeholder, incluindo WhatsApp (*não utilizar informações pessoais*)

## Avaliação das Partes Interessadas

| Nome            | Expectativa no Projeto | Influência    | Importância / Poder | Apoio       | Observações   |
|-----------------|------------------------|---------------|---------------------|-------------|---------------|
|Rogério Greco        | Que o projeto seja bem planejado e relevante para segurança pública| Alta|Alta| Positivo| A principal parte interessada externa|
|Lucas Meira Duque    | Que o projeto seja eficiente e escalável|Alta|Alta|Positivo|Responsável geral do projeto|
|João Gabriel Mendonça|Ser capaz de identificar rapidamente problemas ou mudanças nos requisitos do cliente e trabalhar para ajustar a plataforma conforme necessário|Média|Baixa|Positivo|Canal de comunicação entre o cliente e o projeto|
|Nathália de Carvalho | Garantir que o software seja desenvolvido com as melhores práticas de segurança, protegendo dados sensíveis e previnindo vulnerabilidades |Média|Média|Positivo|Responsável pela segurança e pelo desenvolvimento do software necessário para o projeto|
|Luís Campelo     |Desenvolver e manter a integração da plataforma com sistemas externos, como bancos de dados criminais, sistemas de vigilância por vídeo e outros softwares de segurança pública                      |Média|Média|Positivo|Responsável pelo desenvolvimento de software e pela inteegração com o banco de dados|


> Opções de avaliação:
> - Expectativa: descrição da expectativa da parte interessada no projeto.
> - - Ex.: Diminuição do tempo de realização das tarefas, aumento da produtividade, aumento da satisfação do cliente, etc.
> - Influência: Alta, Média, Baixa
> - Importância: Alta, Média, Baixa
> - Apoio: Positivo, Negativo, Neutro
> - Observações: Informações adicionais, para o cliente.

```diff
+ Tarefa 01
+ Fim da seção a ser atualizada.
```


-----
```diff
+ Tarefa 02
+ Termo de Abertura do Projeto
```

# Termo de Abertura do Projeto

> O Termo de Abertura do Projeto (TAP) representa o ponto de partida oficial para o empreendimento. 
> Ele sintetiza de maneira clara e concisa os objetivos, escopo, partes interessadas envolvidas, entregas esperadas, cronograma preliminar e recursos necessários para a execução bem-sucedida do projeto. 
> O TAP funciona como um contrato inicial entre a equipe do projeto e as partes interessadas, estabelecendo as bases para uma compreensão compartilhada dos propósitos e limites do projeto. 
> Ao delinear esses elementos de forma detalhada, o Termo de Abertura do Projeto (TAP) fornece uma direção sólida para orientar as atividades subsequentes, facilitando a gestão eficaz do projeto desde o início até o encerramento. 
> Essa documentação garante a clareza, alinhamento e comprometimento de todos os envolvidos, contribuindo assim para o sucesso do projeto.

> Você pode utilizar como referência o seguinte documento:
> [Termo de Abertura do Projeto](artefatos/termo-abertura-projeto.docx)

## Estimativa de Custo

......  COLOQUE AQUI O SEU TEXTO ......

> A avaliação da viabilidade econômica busca determinar a sustentabilidade financeira e o retorno sobre o investimento do empreendimento. 
> Este processo envolve a análise dos custos associados ao projeto, incluindo investimentos iniciais, despesas operacionais e potenciais custos de manutenção. 
> Simultaneamente, são examinados os benefícios esperados, como receitas, economias de custos e ganhos tangíveis e intangíveis. 
> A elaboração de projeções financeiras realistas e a aplicação de métricas como o Valor Presente Líquido (VPL) e a Taxa Interna de Retorno (TIR) contribuem para uma avaliação abrangente da viabilidade econômica do projeto. 
> Este processo permite que os gestores de projeto e as partes interessadas tomem decisões informadas sobre a continuidade, ajustes ou mesmo a interrupção do projeto, garantindo uma alocação eficiente de recursos e maximizando os benefícios econômicos esperados.

......  ATUALIZE OS ITENS DE CUSTO DO SISTEMA. ADICIONE NOVOS OU SUBDIVIDA ITENS, CASO NECESSÁRIO ......

| Item de Custo           | Descrição | Qtd. horas | Valor / hora | Valor total |
|-------------------------|-----------|------------|--------------|-------------|
| Recursos Humanos        |           |2.000       |150           |300.000      |
| Hardware                |50 x DHI-IVS-F7500-P-S2 / 5 x Hack servidor / Equipamentos para rede / Refrigeração         |            |              |5.040.000             |
| Software de terceiros   |Software Dahua Technology (incluso no preço do servidor)           |            |              |             |
| **Total Geral**         |           |            |              |5.340.000             |


## Estimativa de Prazo

> Indique:
> * Prazo previsto (em horas) 
> * Data de início
> * Data de término

* Prazo previsto (em horas): 2000
* Data de início: 01 / 09 / 2024
* Data de término: 20 / 12 / 2024

## Escopo Preliminar e Premissas

> Os requisitos preliminares fornecem uma visão inicial do escopo, funcionalidades-chave e as expectativas a serem atendidas. 
> 
> ***A quantidade mínima de requisitos a serem preenchidos nas seções abaixo não incluem os exemplos previamente fornecidos.***

## Declaração de Escopo

> Você pode utilizar como referência o seguinte documento:
- [Declaração de Escopo](artefatos/declaracao-escopo.docx)

> Enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:
>
> - [Requisitos Funcionais (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
>   correspondem a uma funcionalidade que deve estar presente na
>   plataforma (ex: cadastro de usuário).
>
> - [Requisitos Não Funcionais (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
>   correspondem a uma característica técnica, seja de usabilidade,
>   desempenho, confiabilidade, segurança ou outro (ex: suporte a
>   dispositivos iOS e Android).
>
> Lembre-se que cada requisito deve corresponder à uma e somente uma
> característica alvo da sua solução. Além disso, certifique-se de que
> todos os aspectos capturados nas Histórias de Usuário foram cobertos.
> 
> **Links Úteis**:
> 
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)


### Requisitos Funcionais

......  ATUALIZE OS REQUISITOS FUNCIONAIS DO SISTEMA (MÍNIMO 10) ......

A tabela a seguir apresenta os requisitos funcionais do projeto. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|-------|
|RF-001| O sistema deve identificar pessoas procuradas | ALTA     | 
|RF-002| O sistema deve identificar pessoas desaparecidas| MÉDIA     |
|RF-003| O sistema deve identificar atividades suspeitas             || ALTA     |
|RF-004| O sistema deve notificar forças de segurança             | ALTA     |
|RF-005| O sistema deve identificar armamento             | MÉDIA     |
|RF-006| O sistema              | ALTA     |
|RF-007| O sistema deve notificar forças de segurança             | ALTA     |
|RF-008| O sistema deve notificar forças de segurança             | ALTA     |
|RF-009| O sistema deve notificar forças de segurança             | ALTA     |
|RF-010| O sistema deve notificar forças de segurança             | ALTA     |


### Requisitos Não Funcionais

......  ATUALIZE OS REQUISITOS NÃO FUNCIONAIS DO SISTEMA (MÍNIMO 5) ......

A tabela a seguir apresenta os requisitos não funcionais do projeto. 

|ID     | Descrição do Requisito                                            |Prioridade |
|-------|-------------------------------------------------------------------|-----------|
|RNF-001| O sistema deve ter precisão acima de 90% na identificação de pessoas | MÉDIA     | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s             | BAIXA     | 


### Restrições

......  ATUALIZE AS RESTRIÇÕES DO SISTEMA (MÍNIMO 5) ......

A tabela a seguir apresenta as restrições do projeto. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|-------|
|RE-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RE-002| Emitir um relatório de tarefas no mês   | MÉDIA |


### Contra-Escopo

......  ATUALIZE O CONTRA-ESCOPO DO SISTEMA (MÍNIMO 5) ......

A tabela a seguir apresenta as atividades que não serão executadas no projeto

|ID    | Descrição do Contra-Escopo          | 
|------|-------------------------------------|
|CE-001| Treinamento de modelo de LLM        |
|CE-002| Pesquisa de viabilidade do mercado. |

### Condições para início do Projeto

......  ATUALIZE AS CONDIÇÕES PARA INÍCIO DOS PROJETOS (MÍNIMO 3) ......

A tabela a seguir, apresente as condições para que o projeto seja iniciado.

|ID    | Descrição de Condições para Início do Projeto    | 
|------|--------------------------------------------------|
|CI-001| Assinatura de contrato de prestação de serviços. |
|CI-002| Apresentação de garantias definidas no contrato. |

## Marcos Agendados e Entregas

......  ATUALIZE OS MARCOS AGENDADOS DO PROJETO E AS DATAS PARA ENTREGAS DAS TAREFAS ......

A tabela a seguir, identifique os marcos do projeto e os entregáveis previstos (requisitos).

|ID   | Marco do Projeto                                                  | 
|-----|-------------------------------------------------------------------|
|M-1  | Finalização da instalação do sistema de refrigeração |
|M-2  | Conclusão da infraestrutura de rede               |
|M-3  | Finalização da montagem dos Hacks dos servidores                                                              |
|M-4  | Configuração dos seervidores                                                                  |
|M-5  | Conclusão integração com o sistema de monitoramento existente                                                |
|M-6  | Finalização dos testes                                                                  |

```diff
+ Tarefa 02
+ Fim da seção a ser atualizada.
```

-----
```diff
+ Tarefa 03:
+ Metodologia do Projeto
```

# Metodologia

......  COLOQUE AQUI O SEU TEXTO ......

> Nesta parte do documento, você deve apresentar a metodologia adotada pelo grupo, descrevendo o processo de trabalho baseado nas metodologias ágeis, a divisão de papéis e tarefas e as ferramentas empregadas.
>
> Coloque detalhes sobre o processo utilizado e a implementação do Framework Scrum seguido pelo grupo. 
> O grupo deverá gerenciar as tarefas utilizando o GitHub Project para acompanhar o andamento do projeto, a execução das tarefas e o status de desenvolvimento da solução.
> 
> **Links Úteis**:
> - [Github Project](https://docs.github.com/en/issues/planning-and-tracking-with-projects/creating-projects/creating-a-project)
> - [O que é o GitHub Projects? | Guia de Iniciantes](https://www.youtube.com/watch?v=vxYTpsFKdiQ&ab_channel=JulioArruda)
> - [Introduction to GitHub Project Boards](https://www.youtube.com/watch?v=idZyqNIrt84&list=PLiO7XHcmTslc5hGrbnnmHIb0SeJLTpOEu&ab_channel=MickeyGousset)
> - [11 Passos Essenciais para Implantar Scrum no seu Projeto](https://mindmaster.com.br/scrum-11-passos/)
> - [Scrum em 9 minutos](https://www.youtube.com/watch?v=XfvQWnRgxG0)

## Divisão de Papéis

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente a divisão de papéis e tarefas entre os membros do grupo.
> Indique as responsabilidades de cada membro do grupo no projeto.

## Ferramentas

......  COLOQUE AQUI O SEU TEXTO - SIGA O EXEMPLO DA TABELA ABAIXO  ......

> Liste as ferramentas empregadas no desenvolvimento do projeto, justificando a escolha delas, sempre que possível.
> Todas as ferramentas utilizadas devem ser listadas.
> Qualquer tipo de ferramenta que for utilizada para construção de um artefato deve ser identificada, uma vez que podem ser necessárias alterações.
> A necessidade de uso de licenças e possíveis custos relacionados devem ser indicados.

| Ambiente              | Plataforma         | Link de Acesso             | Justificativa |
|-----------------------|--------------------|----------------------------|---------------|
| Quadro Kanban         | Github             | https://github.com/XXXXXXX | Centralização e organização do projeto no próprio repositório. |
| Repositório de código | GitHub             | https://github.com/XXXXXXX |               |
| Protótipo Interativo  | MavelApp ou Figma  | https://figma.com/XXXXXXX  |               |
| Documentos Textuais   | LibreOffice Writer | N/A                        |               |
| Planilhas e Gráficos  | Google Planilhas   | https://docs.google.com/   |               |
| EAP / WBS             | | | |
| Cronograma do Projeto | | | |
| Matriz RACI           | | | |

```diff
+ Tarefa 03:
+ Fim da seção a ser atualizada.
```

----

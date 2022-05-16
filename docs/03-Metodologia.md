## Metodologia

A metodologia ágil escolhida organizará as relações de trabalho com as ferramentas de desenvolvimento, prototipação e organização de execução de atividades relacionadas ao projeto.

## Relação de Ambientes de Trabalho

Cada fase do projeto tem sua organização e particularidade a depender da plataforma. Visando a facilidade, foi criada a tabela abaixo para consulta.

| **Ambiente** | **Plataforma** | **Link** |
| --- | --- | --- |
| Gestão de código fonte | Github | [https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-1-e1-proj-web-t9-divideae](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-1-e1-proj-web-t9-divideae) |
| Documentos do projeto | Google Drive | [https://drive.google.com/drive/folders/1VvASuXFm08fIh4JpwTRqYHVbFNmUN8vD?usp=sharing](https://drive.google.com/drive/folders/1VvASuXFm08fIh4JpwTRqYHVbFNmUN8vD?usp=sharing) |
| Criação de interface e wireframe | Figma | [https://www.figma.com/proto/j034nrL0A3pREQyeHTZkHu/Wireframe?node-id=24%3A90&amp;scaling=scale-down&amp;page-id=24%3A89](https://www.figma.com/proto/j034nrL0A3pREQyeHTZkHu/Wireframe?node-id=24%3A90&amp;scaling=scale-down&amp;page-id=24%3A89) |
| Gestão de projeto | Github Projects | [https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-1-e1-proj-web-t9-divideae/projects/1](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-1-e1-proj-web-t9-divideae/projects/1) |

## Gestão de código fonte

Objetivando a estabilidade, a integridade e o desenvolvimento do código a partir de um fluxo de trabalho mais ágil e descomplicado para todos, o grupo decidiu por colocar em prática a técnica do Gitflow. O Gitflow surgiu como um modelo concebido por Vicent Driessen, tal método possui como pressuposto uma nova forma de organização do código nas chamadas branches. Ao trabalhar com diversas branches, é necessário termos conhecimento sobre quais branches estão prontas para serem enviadas para os diversos ambientes.

O código presente nas branches, pode ser um código estável, isto é, pronto para ser enviado para produção, um código em desenvolvimento, onde o desenvolvedor está efetivamente trabalhando em novas funcionalidades, ou uma branch com código a ser validado. A grande vantagem do Gitflow é a sua capacidade de ser menos propenso a falhas, uma vez que a equipe usa comandos mais amigáveis para manipular, criar e combinar as branches. Tal modelo resulta na seguinte organização das ramificações:

![](RackMultipart20220516-1-6ekmfl_html_74179ae10fdfc279.png)

**Master** : É a branch estável do projeto. Nela é onde temos o código pronto para ser enviado para produção.

**Develop** : A branch de Develop é baseada na branch master e é a partir dela que são criadas as novas funcionalidades do sistema, que são as branches de features.

**Feature** : É aqui onde as novas funcionalidades são criadas e depois são combinadas com Develop.

**Release:** Após uma série de features a serem entregues, existe um passo de release anterior à combinação entre o conteúdo de Develop com a Master. Alguns commits de preparação podem ser criados nessa etapa para garantir a qualidade do código gerado. Após finalizado, essas alterações são combinadas de volta em ambas as branches develop e master.

**Hotfix** : Caso haja algum bug ou correção a ser feita em produção, o processo de reparo geralmente acontece de maneira segregada das features convencionais. Um hotfix é criado a partir da ramificação Master e combinado de volta na branch Master, para garantir que o bug seja resolvido e também mesclado com a branch Develop, para assim evitar uma possível regressão do bug.

## Gerenciamento do Projeto

A equipe utiliza metodologias ágeis, utilizando o kanban para definição de atividades.

organizada da seguinte maneira:

- Scrum Master: Diego Sobrinho
- Product Owner: Igor Morais
- Equipe de Desenvolvimento
  - Igor Morais
  - André Pinto
  - Paula Perret
  - Diego Sobrinho
- Equipe de Design
  - Cristiano de Mattos

Para organização e distribuição das tarefas do projeto, a equipe está utilizando o Trello estruturado com as seguintes listas:

- **Backlog** : Recebe todas as atividades mapeadas durante a análise do projeto. Prontas para serem priorizadas.
- **Design** : recebe as tarefas e prototipação e wireframe relacionadas ao projeto.
- **A Fazer** : Esta lista representa as tarefas priorizadas a serem desenvolvidas.
- **Em andamento** : Quando iniciada uma tarefa, é movida para este card.
- **Revisão de código** : Recebe as tarefas de código assim que forem concluídas, para aprovação de código.
- **Fase de Teste** : Receber os códigos revisados para serem feitos os testes de sistema.
- **Concluído** : Ficam as tarefas concluídas, revisadas e testadas.
- **Bloquedo** : Quando há algum impedimento que não permite a realização da tarefa por completo.

O quadro kanban do grupo no Trello está disponível através da URL [https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-1-e1-proj-web-t9-divideae/projects/1](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-1-e1-proj-web-t9-divideae/projects/1)

